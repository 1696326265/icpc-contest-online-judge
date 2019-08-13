# icpc-contest-online-judge

使用时直接 bash setup.sh

在 start_time_and_finish_time 按样例格式写起始时间和结束时间

数据格式：

pro/<problem_id>/:

tl 文件 ：一个数 单位秒 ， 没有这个文件则默认 1s

datalist ：若干行，每行一个字符串s表示数据 s.in s.ans ，没有这个文件则默认一组数据 in ans

### Features

没有通过的题在排行榜里会显示尝试了多少次，但不会显示提交时间。

排行榜会无视所有 ac 之后的提交。

如果一道题没有在比赛时间内 ac ，那么排行榜会显示选手在 ac 前的尝试次数 而非 比赛时的尝试此数
