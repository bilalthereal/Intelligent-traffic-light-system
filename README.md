# Intelligent-traffic-light-system
In this Project, I implement Intelligent traffic light system by using c++ language. where cars arrive at a "one-way only" tunnel. Only at most “N” cars in one direction can go through the tunnel at a time. Lights can be RED or GREEN only. If the light turns RED, no car should attempt to enter the tunnel. Otherwise, N cars should be allowed to enter and leave the tunnel. I implement one thread per car. N threads need to be woken up when the light turns GREEN. I use sleep(2) function. We pass M total car as from terminal and pass N how many cars we pass when signal is GREEN. 