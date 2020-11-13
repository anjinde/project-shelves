y   = 年份 (yy or yyyy)
M   = 月份 (MM)
d   = 一个月中的第几天      (dd)
h   = 小时 (0-12)  (hh)
H   = 小时 (0-23)  (HH)
m   = 一小时中的第几分钟 (mm)
s   = 秒   (ss)
S   = 毫秒 (SSS)
z   = 时区 (比如：Pacific Standard Time)
Z   = 时区的时差 (比如：-0800)


yyyy-MM-dd           (2009-12-31)
yyyy-MM-dd HH:mm:ss  (2009-12-31 23:59:59)
HH:mm:ss.SSS         (23:59.59.999)
yyyy-MM-dd HH:mm:ss.SSS   (2009-12-31 23:59:59.999)

 // 两个都是ISO的标准时间格式，即2019-12-05T11:27:55.517+08:00
 public static final String DATE_FORMAT_ISO = "yyyy-MM-dd'T'HH:mm:ss.SSSZZZZZ";
 public static final String DATE_FORMAT_ISO_2 = "yyyy-MM-dd'T'HH:mm:ss.SSSXXX";
