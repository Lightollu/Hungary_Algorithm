# Hungary_Algorithm



最主要的步骤就是寻找增广路径，是这么玩的:
1.排在后面的boy都比较强势,比如boy_D,他发现没有妹子剩给他的时候，他就去抢一个,假设D抢的妹子本来是C的，C的妹子被抢了之后他再去抢B的;
2.B的妹子被抢了，他也试着去抢别人的，这个时候D,C霸占着的妹子B是不敢抢的，但是除了这两个其它的所有妹子B都看不上，没有眼缘;
3.B发现自己妹子被C抢了他还抢不到别人的，这个时候B就不乐意了，给C说老子不干，我死也不会把妹子让给你的;
4.C发现B不是好惹的，妹子被抢了要跟自己玩命，刚好他觉得A的妹子也还行，所以就去把A的妹子抢了
5.A的眼光比较低，几乎所有的妹子他都觉得不错.他的妹子被C抢了后，他再去找其他人的妹子，首先是B的，但B一旦被抢妹子就要跟对方玩命，所以还是算了;
6.这个时候A再看有个妹子其他人都不要，他觉得长得还挺漂亮，所以他就去把这个妹子收了，顺便跟C说原来的那个让给你好了
7.一波下来，D抢人成功，找到一条增广路径

总结下来，有两种恶霸，一种是排在后面的，他抢了的妹子其他人都不要想了；还有一种是没有退路的死守着自己妹子的，你抢了他的他跟你玩命。
把这两种恶霸的妹子给记下来，每次自己妹子被抢了寻找新的猎物时都绕开这些恶霸霸占的妹子。因为他们的妹子是抢不得的，前面已经验证过了，他们的妹子一旦被抢他们就主动或被动地不干了，如果有得商量前面也早就商量好了
