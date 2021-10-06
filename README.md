# QueryBuilder
QueryBuilder php class, Simple Querybuilder class I created for php 
#example of use
$qb = new QueryBuilder("TABLENAME");
// insert data
$data['COLUMN_1'] = "value";
$data['COLUMN_2'] = "value 2;
// generate query
$qry = $qb->insertDb($data);
output = "INSERT INTO TABLENAME (COLUMN_1, COLUMN_2) values("value", "value 2");


