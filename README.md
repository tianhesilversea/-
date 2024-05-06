# -curl -fsSL https://get.docker.com | sh
# systemctl stop firewalld
# mkdir -p /x-ui
# mkdir /x-ui/ssl
# cd /x-ui
# docker run -d --name=x-ui --restart=always --network=host stilleshan/x-ui
# docker cp 19c3:/etc/x-ui/x-ui.db /x-ui/
# docker stop x-ui
# docker rm x-ui
# docker run -d --name=x-ui --restart=always --network=host -v /x-ui/x-ui.db:/etc/x-ui/x-ui.db -v /x-ui/ssl:/ssl stilleshan/x-ui
