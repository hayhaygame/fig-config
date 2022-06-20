# fig-config


 grep Folder s3.txt  | sed 's/\///' | awk '{ print "aws s3 sync s3://aqbucket.ctv/" $1 " E:/S3/" $1 }'
