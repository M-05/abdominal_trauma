# [RSNA 2023 Abdominal Trauma Detection](https://www.kaggle.com/competitions/rsna-2023-abdominal-trauma-detection/overview)

### Quick Start
```
!pip install pydicom nilearn kaggle
```
__Kaggle API__
1. kaggle 접속.
2. setting 접속.
3. `Create New Token` 클릭.
4. kaggle.json 파일 열어서 확인.

__API Key 설정__
```
os.environ['KAGGLE_USERNAME'] = 'your kaggle json username'
os.environ["KAGGLE_KEY"] = 'your kaggle json key'
```

**kaggle API로 데이터 가져오기.**
```
!kaggle competitions download -c rsna-2023-abdominal-trauma-detection
```

__Web Get 으로 데이터 가져오기.__
```
!wget "https://storage.googleapis.com:443/kaggle-competitions-data/kaggle-v2/52254/6307054/upload/public.zip?GoogleAccessId=web-data@kaggle-161607.iam.gserviceaccount.com&Expires=1694657937&Signature=UulbpSX3AAVYvmx95%2BXdWoRdC9xhuzL4zu6M3xQppcKWCwOT06ce9Q27lCSu4pInmGLOM6A4aBvorMPe9SmJ7sEIedapxFJLwxZiyk56UoNAa%2FvUVdr3%2F3eWjTkAKbBeU3gdzlirOV61EE8UuHJK3b3Wfgg%2B1%2B5DhVpmvcBqj255UCT89glX2a5s3SOMPb%2FVAcfMZWbaEKBc%2FUqVwRvYkjWw9YxLV40MrhUZPqA1s8NQ0c9y8bOeIhvrARCThaIYvZroidq75tPlpjr1QW1JjnCumZGapYy3n%2BqQRIgLrF3S%2Fvttli3kYdjT5NBc9CPRWIAqbCgDNdpTNlgzmRJP8g%3D%3D&response-content-disposition=attachment%3B+filename%3Drsna-2023-abdominal-trauma-detection.zip"
```

__Data Explorer__
|type|size|files|
|----|----|----|
|dcm, nii, csv, parquet|460.34GB|1,500,869|

---
[Notion](https://m05.notion.site/Abdominal-Trauma-Detection-9271ea0affbc445796d9e1e9060f0d61?pvs=4)
