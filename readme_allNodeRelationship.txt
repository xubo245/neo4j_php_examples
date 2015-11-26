readme_allNodeRelationship.txt
1.setup neo4j and neoclient
2.create graph in neo4j by create.txt
3. modify you file in addConnection('default','http','localhost',7474,true,'user','password')
4.look :http://localhost/phpclient/tests/allNodeRelationship.php(phpclient is neoclient)
5.result:
hello php neo4j:
2.3.0-M02
num 1 :Person -> name =>Id: 129 =>name: S
num 2 :Person -> name =>Id: 130 =>name: A1
num 3 :Person -> name =>Id: 131 =>name: A2
num 4 :Person -> name =>Id: 132 =>name: A3
num 5 :Person -> name =>Id: 133 =>name: A4
num 6 :Person -> name =>Id: 134 =>name: A5
num 7 :Person -> name =>Id: 135 =>name: B1
num 8 :Person -> name =>Id: 136 =>name: B2
num 9 :Person -> name =>Id: 137 =>name: B3
num 10 :Person -> name =>Id: 138 =>name: D
node end

num 1 : =>Id: 147 =>Type: KNOWS =>startId: 129 =>endId: 130
num 1 : =>Id: 153 =>Type: KNOWS =>startId: 129 =>endId: 135
num 1 : =>Id: 148 =>Type: KNOWS =>startId: 130 =>endId: 131
num 1 : =>Id: 149 =>Type: KNOWS =>startId: 131 =>endId: 132
num 1 : =>Id: 150 =>Type: KNOWS =>startId: 132 =>endId: 133
num 1 : =>Id: 151 =>Type: KNOWS =>startId: 133 =>endId: 134
num 1 : =>Id: 152 =>Type: KNOWS =>startId: 134 =>endId: 138
num 1 : =>Id: 154 =>Type: KNOWS =>startId: 135 =>endId: 136
num 1 : =>Id: 155 =>Type: KNOWS =>startId: 136 =>endId: 137
num 1 : =>Id: 156 =>Type: KNOWS =>startId: 137 =>endId: 138
relationship end
