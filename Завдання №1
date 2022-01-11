def direction(facing, turn):
    if (turn>-1080 and turn<1080):
        f= ['N','NE','E','SE','S','SW','W','NW']
        if turn>0: 
            p=turn/45
            k=int(f.index(facing)+p)
            if k>7:
                while k>=7:
                    k=k-8
            return(f[k])
        elif turn<0:
            p=turn/-45
            k=int(f.index(facing)-p)
            if k<0:
                while k<=0:
                    k=k+8
            return(f[k])
    else:return 0
