boundary_x, boundary_y = [int(i) for i in input().split()]

pos_x, pos_y = 0, 0

while True:
    input_x, input_y = [int(i) for i in input().split()]
    if input_x == 0 and input_y == 0:
        break

    pos_x += input_x
    pos_y += input_y

    if pos_x > boundary_x:
        pos_x = boundary_x

    elif pos_x < 0:
        pos_x = 0
    
    if pos_y > boundary_y:
        pos_y = boundary_y

    elif pos_y < 0:
        pos_y = 0

    print(pos_x, pos_y)
