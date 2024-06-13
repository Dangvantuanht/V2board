

## Cấu hình node bằng Xrayr
 
 - (https://github.com/Dangvantuanht/XrayR-release)



##Các bước di chuyển bảng điều khiển：

    git remote set-url origin [https://github.com/Dangvantuanht/V2board ]
    git checkout master  
    ./update.sh  


hực hiện theo các bước bên dưới để làm mới bộ đệm cài đặt và khởi động lại hàng đợi:

    php artisan config:clear
    php artisan config:cache
    php artisan horizon:terminate


# **V2Board**

- PHP7.3+
- Composer
- MySQL5.5+
- Redis
- Laravel



## Document
[Click](https://v2board.com)



## How to Feedback
Follow the template in the issue to submit your question correctly, and we will have someone follow up with you.
