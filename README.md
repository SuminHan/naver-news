# naver-news
네이버 종합 많이 본 뉴스를 날짜별로 전부
Scrapy를 사용해서 크롤링 하는 코드입니다.

결과 파일은 result 폴더에 result.xlsx, result.csv, result.csv로 있습니다.

# 사용법
```bash
git clone https://github.com/carcdrcons/naver-news
cd naver-news
pip install -r requirements.txt

scrapy crawl naver_news -o naver_news.jl
python convert_jsonlines_to_other_format.py
```
