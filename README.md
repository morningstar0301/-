# -mongodb 导入导出
./mongoexport -d rc -c articles --type=json  -q '{"book":{"$oid":"634d1cde1208966bf1bcd54e"}}' -o /data/release/D1.json

 ./mongoimport -d rc -c articles --type=json --file /data/release/Q2.json

 #-
