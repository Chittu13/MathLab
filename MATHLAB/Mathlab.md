# 2D wave form

```MATHLAB
t=-pi:0.1:pi;
x=sin(t)
plot(t,x)
title('sinewave','fontsize',20);
xlable('amplitude','fontsize',20);
ylable('time','fontsize',20);
```


# 3D wave form

```MATHLAB
t=-pi:0.1:pi;
x=sin(t);
y=x.*sin(t);
plot3(t,x,y)
title('sinewave');
xlable('amplitude');
ylable('time');
```
