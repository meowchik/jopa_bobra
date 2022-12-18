# jopa_bobra
z=10 x=10 c=10 def setup():     size(600,400) def draw():     global z,x,c     background(0)     triangle(300,200,z,300,400,300)     triangle(300,x,200,100,400,100)      triangle(300,100,500,c,200,200)     z-=1     x-=1     c-=1
