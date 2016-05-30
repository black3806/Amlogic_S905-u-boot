# Amlogic_S905-u-boot
U-boot for platform Amlogic S905

Скачать отсюда :

http://openlinux.amlogic.com:8000/deploy/

gcc-linaro-aarch64-none-elf-4.8-2013.11_linux.tar
CodeSourcery.tar.gz

Распаковать в /opt

Сборка 

./mk gxb_p200_v1

или

./mk gxb_p201_v1

Если будет ошибка (на системах, где много разных компилятор) можно использовать скрипты, где сразу прописаны нужные.

./make_p200

или 

./make_p201
