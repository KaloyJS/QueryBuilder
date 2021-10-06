# QueryBuilder
QueryBuilder php class, Simple Querybuilder class I created for php 
# example of use
$qb = new QueryBuilder("TABLENAME"); <br />
// insert data <br />
$data['COLUMN_1'] = "value"; <br />
$data['COLUMN_2'] = "value 2; <br />
// generate query <br />
$qry = $qb->insertDb($data); <br />
output = "INSERT INTO TABLENAME (COLUMN_1, COLUMN_2) values("value", "value 2");


