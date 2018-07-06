# java_perfeng
Java Performance Engineering 

# How to checkout do the your change and do the checkin
git clone https://github.com/mpsinterns/java_perfeng.git
cd java_perfeng


# how to extract the method list
1. rightclick inspect element
2. in the source right click and copy the xpath
3. copy the first element
4. get the second element

namelist=($x('/html/body/div[4]/div[3]/ul/li/ul/li/ul[1]/li/pre'))
namelist=($x('/html/body/div[4]/div[3]/ul/li/ul/li/ul[2]/li/pre'))

namelist=($x('/html/body/div[4]/div[3]/ul/li/ul/li/ul[*]/li/pre'))
var s = "";
for(var i = 0; i < 100; i += 1) {
  s += citylist[i].outerText + " \n ";
}
console.log(s);
