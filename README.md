# Jitsi

Chạy file jitsi.sh

    cd /root/ && git clone https://github.com/tuanpa-tpa/backup-jitsimeet.git
    chmod +x jitsi.sh
    ./jitsi.sh

Jitsi tự động cài đặt Nginx, sau đó truy cập nginx: /etc/nginx/sites-available/<<domain>>.conf sửa mục root mặc định thành /root/backup-jitsimeet

DOCUMENT: https://jitsi.github.io/handbook/docs/devops-guide/devops-guide-quickstart
