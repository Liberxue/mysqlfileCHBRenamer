# mysqlfileCHBRenamer
PERL SHELL batch modify Chinese database and server, Chinese file name, old system iteration

```
find ./ -name '*.mp4' >mp4ls.txt
open( FH, "mp4ls.txt" ); #打开文件
foreach $line ( <FH> ){ #循环读取文件
$line =~ s/\x0D?\x0A?$//; #取得一行，去掉结尾换行符
@datas = split(" ",$line); #把空格当中分隔符，取得数据
$dats[0]; #Steve
$dats[1]; #Blenheim
$dats[2]; #101
rename $dats[0],`date +%Y%m%d`; 
}




shell 
find ./ -name '*.mp4' >mp4ls.txt


shell版本//rename 要考虑文件名空格和各种括号

for line in $(cat mp4ls.txt)
do 
    echo "File:${line}"；
  # mv ${line} $(date +%Y%m%d%s).mp4
done > list2.txt


perl ：无限制。。。

my @array = open FileHandle,'<mp4ls.txt>';
my $date = qx{date +"%Y%m%d%s"}. 'mp4';
qx{mv $_ $date} for @array;
close FileHandle;
 i=$(($i+1))
 sleep 6

额预热无语  飞速发 iu 
32423 。34553



for line in $(cat mp4ls.txt)
do 
    echo "File:${line}"；
 mysql -uroot -p123456 test -e "UPDATE t_contents SET test = 'sdsfjkkjsdjfjs' WHERE filename=${line}"
done > list2.txt

#listname 为原来文件名 listrename为修改后文件名
cat list| awk 。 | while read platform  listname  listrename
do
    echo $listname"   "$listrename
     mysql -uroot -proot test -e "UPDATE t_contents SET test = $listrename WHERE filename=$listname"
done




for line in $(cat JPG.txt)
do 
    echo "File:${line}"；
  # mv ${line} $(date +%Y%m%d%s).JPG
done 


while line in $(cat JPG.txt)
do 
    echo "File:${line}"；

done 


while read line  
do  
  echo $line;  

  
done <JPG.txt

find ./ -name '*.JPG' >JPG.txt。


>123.txt

i=0;
 while read line  in $(cat JPG.txt)
  do        
         echo $line  
          let i=i+1  
  done
 #echo "$i"  



mv ${line} $(date +%Y%m%d%s).JPG










for line in $(cat JPG.txt)
do 
    echo "File:${line}"；
    mv  ${line} $(date ""+%Y%m%d%s).JPG
done




find ./ -name '*.JPG' >JPG.txt



for line in `catmp4ls.txt`
do 
    echo "File:${line}"
done




for i in *.mp4;do mv $i $(sed "s/.MP4/" <<<$i);done



for var in `ls *.mp4`; do mv "$var" `echo "$var" |awk -F  '{print $1 `date +%Y%m%d` $2}'`; done
1


echo for var in `ls *.mp4`


open( FH, "mp4ls.txt" ); #打开文件
foreach $line ( <FH> ){ #循环读取文件
$line =~ s/\x0D?\x0A?$//; #取得一行，去掉结尾换行符
@datas = split(" ",$line); #把空格当中分隔符，取得数据
$dats[0]; #Steve
$dats[1]; #Blenheim
$dats[2]; #101
#接下来处理取得的数据
}
```
