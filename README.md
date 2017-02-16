credmap: Kimlik Bilgileri Eşleştiricisi

Yazılım elinizde olan eposta ve varsayılan şifresini,diğer sosyal platformlarda deneme yanılma ile test eder. Eğer şifreniz ve eposta adresiniz bu siteler ile eşleşirse başarılı giriş yaparak sizi bilgilendirir. Sadece eposta ve şifreyi yazarsınız yazılım otomatik olarak tüm sitelerde teste başlar

pip install website

unzip credmaptr.zip

chmod +x ./credmap.py

Örnek Kullanım

./credmap.py --kullaniciadi janedoe --email janedoe@email.com
./credmap.py -u johndoe -e johndoe@email.com --exclude "github.com, live.com"
./credmap.py -u johndoe -p abc123 -vvv --only "linkedin.com, facebook.com"
./credmap.py -e janedoe@example.com --verbose --proxy "https://127.0.0.1:8080"
./credmap.py --load creds.txt --format "e.u.p"
./credmap.py -l creds.txt -f "u|e:p"
./credmap.py -l creds.txt
./credmap.py --list
Test için Site Eklemek

yazilim dizinindeki websites klasörüne eklediğniz XML dosyaları ile website test isteği oluşturabilirsiniz. Bunun için varsayılan XML şablonuna uygun olarak oluşturmanız gerekiyor. Wiki.
