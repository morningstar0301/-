# -mongodb 导入导出
./mongoexport -d rc -c articles --type=json  -q '{"book":{"$oid":"634d1cde1208966bf1bcd54e"}}' -o /data/release/D1.json --sort={"name":1} #排序  windows下只能用双引号，并且用\"转义

 ./mongoimport -d rc -c articles --type=json --file /data/release/Q2.json

 #-MP4瘦身
ffmpeg -i 2023-10-ITERO-Msg02-E.mp4 -fs 200M -s 640x320 -c:a copy 2.mp4

#chm转 html :
hh -decompile D:\html D:\test.chm

#音频截取：
ffmpeg -i c1.mp3 -ss xx:xx:xx -to xx:xx:xx xx.mp3

iSilo 4.3 win  注册码 KJNX9TKNP4TG94U7


ST mongodb 启动方法： mongod --config /etc/mongod.conf

-------git 操作-------------
git add . 的作用是‌将当前目录（及其子目录）中所有新创建的文件（未跟踪）和内容已修改的文件（已跟踪）添加到Git的‌暂存区（staging area）‌，为后续提交（commit）做准备。‌
git commit
git push origin main  # 推送合并结果
