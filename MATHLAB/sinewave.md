t = -pi:0.1:pi;
a=sin(t);
plot(t,a,'r')
title('sinewave');
xlabel('amplitude','fontsize',20);
ylabel('time');
hold on
b=cos(t);
plot(t,b,'b')
title('sinewave');
xlabel('amplitude');
ylabel('time');


