//截取#之前的字符串
String str = "sdfs#d";
str.substring(0, str.indexOf("#"));


//截取之后的字符 
String userId = "21321321?u=2132132132";
String userIdJiequ = userId.substring(userId.indexOf("?u="));