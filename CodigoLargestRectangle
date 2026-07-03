def largestRectangle(h):
    stack = []
    max_area = 0
    n = len(h)

    for i in range(n + 1):
        # Barra ficticia de altura 0 al final para vaciar la pila
        current_height = 0 if i == n else h[i]

        while stack and current_height < h[stack[-1]]:
            height = h[stack.pop()]

            if stack:
                width = i - stack[-1] - 1
            else:
                width = i

            max_area = max(max_area, height * width)

        stack.append(i)

    return max_area
