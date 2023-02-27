====HƯỚNG DẪN CRAWL DỮ LIỆU TỪ WEB=====

*Cài đặt môi trường và Scrapy:
1. Cài đặt Anaconda: https://docs.anaconda.com/anaconda/install/windows/
2. Cài đặt Scrapy: https://docs.scrapy.org/en/latest/intro/install.html

*Cách chạy Scarpy sau khi cài đặt thành công:
1. Mở terminal, gõ lệnh sau "src/crawler"
2. Sau khi được đưa vào thư mục trên, gõ tiếp trên terminal lệnh "scrapy crawl full2ImdbCrawler -o data.csv -t csv"
3. Sau khi hoàn tất, tiếp tục gõ lệnh "scrapy crawl full2MpaaCrawler -o data_mpaa.csv -t csv"
4. Mở lại thư mục crawler, ta sẽ thấy 2 file mới được tạo là "data.csv" và "data_mpaa.csv". Di chuyển 2 file đó vào thư mục dataset
5. Mở terminal và gõ lệnh "cd.." rồi gõ "python join_data.py". Ta sẽ thu được 1 file mới tên "data_joined.csv". Chuyển file đó vào thư mực dataset
