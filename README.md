# casa_oo_workshop

OO workshop 题目：

1.实现一个停车场，提供停车和取车的功能；

2.实现一个停车小弟，提供代客停车取车功能，一个小弟可以管理多个停车场，停车逻辑按照停车场顺序停，第一个停满，再停到第二个...

3.实现另外一个停车小弟，每次 优先把车停到空位最多的停车场里；

4.实现第三个小弟，每次把车停到空置率最高的停车场里；

5.重构到策略

6.实现一个停车场经理，可以管理多个停车小弟，提供停取车功能；

7.实现一个超级停车场经理，可以管理多个停车经理，提供停取车功能；

8.重构出Parkable接口

9.实现report功能:

```
                    ParkManager:
                    -ParkBoy:
                    --ParkLot(0/2)
                    --ParkLot(0/2)
                    -ParkBoy:
                    --ParkLot(0/2)
                    --ParkLot(0/2);
```
10.重构到visitor