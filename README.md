# sql

// show what accounts were worked by agent desk //
select * from CDS.DAT where DAT_USER_ID = 'AMO' AND DAT_TRX_DATE_O = '2016-07-19' AND DAT_TYPE IN ('S', 'C', 'H')
