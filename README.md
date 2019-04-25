# Automatic-Differentiation-FrameWork
It is a small-scale differentiation framework like PyTorch, TensorFlow. All the differentiation rules like chaining.
Some of the rules implemented are as follows:
    d_neg: 
          z = -y we can perform (dz/dx)
    d_add:
          z = y1+ y2 we can perform (dz/dx) by applying rule dz/dx = (dy1/dx)+(dy2/dx).
    d_sub: 
          z = y1 - y2 we can perform (dz/dx) by applying rule dz/dx = (dy1/dx) - (dy2/dx).
    d_mul:
          z = y1.y2 we can perform (dz/dx) by applying the rule dz/dx = (dy1/dx).y2 + y1(dy2/dx).
    d_truediv:
          z = y1/y2 we can perform (dz/dx) by applying the rule dz/dx = ((dy1/dx)y2 - y1.(dy2/dx))/(y2)^2
    and for derivative for power and tan.
    
            
