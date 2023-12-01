
<div align="center"><img src="https://github.com/69learn/tuic-panel/blob/main/v2raya.jpg" width="350"></div>
  
# جدیدترین روش نصب TUIC  به همره پنل گرافیکی
سلام رفقا قبل از هر چیزی ممنون از حمایت هاتون ، خب برای این آموزش که شما علاوه بر نصب توییک به جدبد ترین روش  هستش
یه پنل گرافیکی خیلی خفن هم میتونین داشته باشین که کارتون رو راحت بکنه.


# Telegram Channel: 

https://t.me/sixtininelearn



# Suggested OSs

- Ubuntu 22


# نصب پنل گرافیکی v2raya
<div align="center"><img src="https://github.com/69learn/tuic-panel/blob/main/v1.png" width="1500"></div>

````
curl -sSL https://apt.v2fly.org/pubkey.gpg | sudo apt-key add -
````
````
echo "deb [arch=amd64] https://apt.v2fly.org/ stable main" | sudo tee /etc/apt/sources.list.d/v2ray.list
````

````
sudo apt-get update
````
````
sudo sh -c "$(wget -qO- https://hubmirror.v2raya.org/v2rayA/v2rayA-installer/raw/main/installer.sh)" @ --with-v2ray
````
````
sudo sh -c "$(wget -qO- https://hubmirror.v2raya.org/v2rayA/v2rayA-installer/raw/main/installer.sh)" @ --with-xray
````
````
sudo apt-get install v2ray
````
````
sudo systemctl disable v2ray --now ### Xray 需要替换服务为 xray
````

````
wget -qO - https://apt.v2raya.org/key/public-key.asc | sudo tee /etc/apt/keyrings/v2raya.asc
````

````
echo "deb [signed-by=/etc/apt/keyrings/v2raya.asc] https://apt.v2raya.org/ v2raya main" | sudo tee /etc/apt/sources.list.d/v2raya.list
sudo apt update
````

````
sudo apt install v2raya v2ray ## 也可以使用 xray 包
````

````
sudo systemctl start v2raya.service
````
````
sudo systemctl enable v2raya.service
````

# reality-ezpz پنل

````
bash <(curl -sL https://raw.githubusercontent.com/aleskxyz/reality-ezpz/master/reality-ezpz.sh)
````

````
bash <(curl -sL https://bit.ly/realityez) -m
````





<!-- 
# نحوه استفاده از ipv6  روی نپسترنت
<p align="center">
    <a href="https://youtu.be/emQSNXc1kpA">
        <img
            style=
                "display: block;
                margin-left: auto;
                margin-right: auto;
                width: 70%;"
            src="./src/youtube0012.jpg"
            alt="BBR vs Cubic vs Hybla vs PCC">
        </img>
    </a>
</p> -->



