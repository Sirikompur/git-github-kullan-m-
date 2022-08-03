# git-github-kullan-m-
madde madde açılım
Önce burada bir repository oluşturuyorsun.
Sonra kendi masaüstünde veya flaşında da aynı isimde bir dosya oluşturuyorsun.
sonra masaüstündeki veya flaşındaki o dosyanın adresiyle komut penceresini açıyorsun.
sonra şunları sırasıyla yapıyorsun :

//testone klasörümüzün içine girelim

cd Desktop/testone

//giti aktif hale getirelim

git init

//klasörünün içindeki tüm dosyaları . ile ekliyoruz.

git add .

githup user email bilgimizi

git config --global user.email "o....@gmail.com"

githup kullanıcı adımızı

git config --global user.name "se...."

repoya yorum ile commit atıyoruz.

git commit -m "ilk Dosyaları yükledim"

branch olarak main olduğunu belirtiyoruz.

git branch -M main

repo oluşturduğumuz linki ve git adı belirliyoruz

git remote add origin https://sdfsfwsfwsef/tfrdhj.git

projemizi GitHub’a taşıyoruz. git adı yukarda oluşturdugumuz nextdeneme idi

git push -u origin main


Eğer remote linkini girdiğinde 

error: remote origin already exists.

hatası alıyorsan bil ki öönceki kurduğun remote linki hala ayakta. Ve bu yüzden klasörünü yüklerken

hatayla karşılaşabilirsin.

önceki remote linkini kapatıp şimdikini aktif hale getirmek için : 

git remote set-url origin ...yeni remote link... 

yazıp hallediyoruz.
