# data-scraping-to-database
# Bina.az Data Scraper & SQL Server Loader

Bu layihə **bina.az** saytından daşınmaz əmlak elanlarını avtomatlaşdırılmış şəkildə çəkir, məlumatları təmizləyir və **Microsoft SQL Server** verilənlər bazasına yükləyir.

---

## Vacib Hüquqi Qeyd

Bu layihə yalnız **təhsil**, **şəxsi istifadə** və **tədqiqat məqsədləri** üçün nəzərdə tutulub. Bina.az saytının **istifadə şərtlərinə**, **müəllif hüquqlarına** və **məlumatların qorunması qanunlarına** riayət etmək vacibdir.

Layihəni istifadə edərkən aşağıdakıları nəzərə alın:

- Saytın serverinə həddindən artıq yük yaratmayın (müntəzəm fasilələr əlavə edin).  
- Qeyd: Bu layihə rəsmi API istifadə etmir, məlumatlar veb səhifədən avtomatlaşdırılmış scraping yolu ilə toplanır.

---

## Funksionallıq

- **Dinamik veb scraping**: Selenium və BeautifulSoup ilə elan məlumatlarını toplayır.  
- **Məlumatların təmizlənməsi və strukturlaşdırılması**.  
- **Yenilənən məlumatların bazaya əlavə olunması**.

---

## Texniki Tələblər

- Python  
- `selenium`, `beautifulsoup4`, `pandas`, `pyodbc`, `sqlalchemy`, `time`,`tqdm`,`re` və ya digər SQL Server bağlantı modulu  
- Microsoft SQL Server  
- ChromeDriver
