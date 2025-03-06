# Jwana Restaurant Menu

This is the official menu for Jwana Restaurant. The menu includes a variety of items including Shawarma Saj Sandwiches, Shawarma Saj Meals, Mixed Shawarma Meals, Saj Snacks, Lebanese Manakish, Jwana Mutabbaqat, Jwana Pizza, Beverages, Additional Orders, and Extras.

## How to Publish the Website

1. **Create a new repository on GitHub:**
   - Go to your GitHub account and click on the "+" button in the top right corner, then select "New repository".
   - Name the repository `jwana-restaurant-menu`.
   - Make sure the repository is public and click "Create repository".

2. **Upload the website files to the repository:**
   - Click on "Uploading an existing file" on the repository's main page.
   - Drag and drop the files `README.md` and `index.html` into the upload area or choose the files from your computer.
   - After uploading the files, click "Commit changes" to publish them in the repository.

3. **Enable GitHub Pages:**
   - Go to the repository settings by clicking on the "Settings" tab.
   - In the side menu, find the "Pages" section and click on it.
   - In the "Source" section, select the branch that contains your website files (usually `main` or `master`) and choose `/root` as the source folder.
   - Click "Save".

4. **Access the website:**
   - After enabling GitHub Pages, a link to your website will be generated. You can find this link in the "Pages" section of the repository settings.
   - Use this link to access your published website.

### Example GitHub Pages Link
If your GitHub username is `ehabbshairah` and the repository name is `jwana-restaurant-menu`, the link to your website would be:
```
https://ehabbshairah.github.io/jwana-restaurant-menu/
```<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jwana Restaurant Menu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            text-align: right;
        }
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .menu-section {
            margin-bottom: 20px;
        }
        .menu-section h2 {
            background-color: #f8b400;
            padding: 10px;
            margin: 0;
            font-size: 1.5em;
        }
        .menu-item {
            display: flex;
            justify-content: space-between;
            padding: 5px 10px;
            border-bottom: 1px solid #ccc;
        }
        .menu-item span {
            font-size: 1.2em;
        }
    </style>
</head>
<body>
    <header>
        <h1>جوانا عايش جوانا</h2>
        <h2>قائمة طعام</h2>
    </header>
    <div class="menu-section">
        <h2>صاج شاورما ساندويش</h2>
        <div class="menu-item">
            <span>صاج شاورما دجاج</span>
            <span>1.50</span>
        </div>
        <div class="menu-item">
            <span>صاج شاورما لحمة</span>
            <span>1.75</span>
        </div>
    </div>
    <div class="menu-section">
        <h2>صاج شاورما وجبات</h2>
        <div class="menu-item">
            <span>وجبة شاورما عادي دجاج</span>
            <span>2.50</span>
            <span>لحمة</span>
            <span>2.75</span>
        </div>
        <div class="menu-item">
            <span>وجبة شاورما سوبر دجاج</span>
            <span>3.00</span>
            <span>لحمة</span>
            <span>3.25</span>
        </div>
        <div class="menu-item">
            <span>وجبة شاورما دبل دجاج</span>
            <span>3.60</span>
            <span>لحمة</span>
            <span>4.00</span>
        </div>
        <div class="menu-item">
            <span>وجبة شاورما تريبل دجاج</span>
            <span>5.00</span>
            <span>لحمة</span>
            <span>6.00</span>
        </div>
        <div class="menu-item">
            <span>وجبة شاورما توفير دجاج</span>
            <span>9.00</span>
            <span>لحمة</span>
            <span>11.00</span>
        </div>
        <div class="menu-item">
            <span>وجبة شاورما عائلي دجاج</span>
            <span>14.00</span>
            <span>لحمة</span>
            <span>16.00</span>
        </div>
    </div>
    <div class="menu-section">
        <h2>وجبات مكس شاورما</h2>
        <div class="menu-item">
            <span>وجبة دبل مكس</span>
            <span>4.00</span>
        </div>
        <div class="menu-item">
            <span>وجبة توفير مكس</span>
            <span>9.00</span>
        </div>
        <div class="menu-item">
            <span>وجبة عائلية مكس</span>
            <span>15.00</span>
        </div>
    </div>
    <div class="menu-section">
        <h2>سناكات صاج</h2>
        <div class="menu-item">
            <span>زنجر ساندويش</span>
            <span>1.75</span>
            <span>وجبة</span>
            <span>3.00</span>
        </div>
        <div class="menu-item">
            <span>زنجر مع تيركي ساندويش</span>
            <span>2.00</span>
            <span>وجبة</span>
            <span>3.25</span>
        </div>
        <div class="menu-item">
            <span>شيش طاووق ساندويش</span>
            <span>2.00</span>
            <span>وجبة</span>
            <span>3.25</span>
        </div>
        <div class="menu-item">
            <span>فاهيتا ساندويش</span>
            <span>3.00</span>
            <span>وجبة</span>
            <span>3.75</span>
        </div>
        <div class="menu-item">
            <span>برغر دجاج 150 غم ساندويش</span>
            <span>3.00</span>
            <span>وجبة</span>
            <span>3.75</span>
        </div>
        <div class="menu-item">
            <span>برغر لحمة 150 غم ساندويش</span>
            <span>3.25</span>
            <span>وجبة</span>
            <span>4.00</span>
        </div>
        <div class="menu-item">
            <span>ساندويش بطاطا</span>
            <span>1.25</span>
        </div>
    </div>
    <div class="menu-section">
        <h2>مناقيش لبنانية</h2>
        <div class="menu-item">
            <span>مكس أجبان</span>
            <span>2.25</span>
        </div>
        <div class="menu-item">
            <span>جبنة قشقوان</span>
            <span>2.00</span>
        </div>
        <div class="menu-item">
            <span>جبنة شدر</span>
            <span>1.50</span>
        </div>
        <div class="menu-item">
            <span>زعتر وزيت</span>
            <span>1.00</span>
        </div>
        <div class="menu-item">
            <span>هوت دوج وجبنة</span>
            <span>2.25</span>
        </div>
        <div class="menu-item">
            <span>تيركي وجبنة</span>
            <span>2.25</span>
        </div>
        <div class="menu-item">
            <span>منقوشة جوانا</span>
            <span>2.25</span>
        </div>
        <div class="menu-item">
            <span>سبسيال</span>
            <span>3.00</span>
        </div>
        <div class="menu-item">
            <span>حبش مدخن بالدجاج</span>
            <span>2.25</span>
        </div>
        <div class="menu-item">
            <span>بيض</span>
            <span>1.00</span>
        </div>
        <div class="menu-item">
            <span>بيض وجبنة</span>
            <span>1.50</span>
        </div>
        <div class="menu-item">
            <span>هوت دوج وبيض</span>
            <span>1.50</span>
        </div>
        <div class="menu-item">
            <span>سلامي وجبنة</span>
            <span>2.25</span>
        </div>
    </div>
    <div class="menu-section">
        <h2>مطبّقات جوانا</h2>
        <div class="menu-item">
            <span>مطبقة ستيك وجبنة</span>
            <span>2.75</span>
        </div>
        <div class="menu-item">
            <span>مطبقة شيش طاووق</span>
            <span>2.50</span>
        </div>
        <div class="menu-item">
            <span>مطبقة فاهيتا</span>
            <span>2.50</span>
        </div>
        <div class="menu-item">
            <span>مطبقة زنجر</span>
            <span>2.75</span>
        </div>
        <div class="menu-item">
            <span>مطبقة شاورما</span>
            <span>2.50</span>
        </div>
        <div class="menu-item">
            <span>مطبقة مش رح ئول</span>
            <span>2.75</span>
        </div>
        <div class="menu-item">
            <span>مطبقة ايطالي دجاج</span>
            <span>3.00</span>
        </div>
        <div class="menu-item">
            <span>مطبقة إيطالي لحمة</span>
            <span>3.50</span>
        </div>
        <div class="menu-item">
            <span>مطبقة كاساديا دجاج</span>
            <span>3.00</span>
        </div>
        <div class="menu-item">
            <span>مطبقة كاساديا لحمة</span>
            <span>3.50</span>
        </div>
        <div class="menu-item">
            <span>مطبقة باربكيو</span>
            <span>3.00</span>
        </div>
        <div class="menu-item">
            <span>مطبقة جاج بالكريمة</span>
            <span>2.75</span>
        </div>
        <div class="menu-item">
            <span>مطبقة تيركي وجبنة</span>
            <span>2.25</span>
        </div>
        <div class="menu-item">
            <span>مطبقة هوت دوج وجبنة</span>
            <span>2.25</span>
        </div>
        <div class="menu-item">
            <span>مطبقة مكس أجبان</span>
            <span>2.25</span>
        </div>
        <div class="menu-item">
            <span>مطبقة قشقوان</span>
            <span>2.00</span>
        </div>
        <div class="menu-item">
            <span>مطبقة سلامي</span>
            <span>2.25</span>
        </div>
        <div class="menu-item">
            <span>مطبقة نوتيلا</span>
            <span>2.25</span>
        </div>
    </div>
    <div class="menu-section">
        <h2>بيتزا جوانا</h2>
        <div class="menu-item">
            <span>بيتزا دجاج وسط</span>
            <span>4.25</span>
            <span>كبير</span>
            <span>5.50</span>
        </div>
        <div class="menu-item">
            <span>بيتزا الفريدو دجاج وسط</span>
            <span>4.50</span>
            <span>كبير</span>
            <span>5.75</span>
        </div>
        <div class="menu-item">
            <span>بيتزا لحمة وسط</span>
            <span>4.75</span>
            <span>كبير</span>
            <span>6.00</span>
        </div>
        <div class="menu-item">
            <span>بيتزا خضار وسط</span>
            <span>3.25</span>
            <span>كبير</span>
            <span>4.50</span>
        </div>
        <div class="menu-item">
            <span>بيتزا سلامي وسط</span>
            <span>3.50</span>
            <span>كبير</span>
            <span>5.00</span>
        </div>
        <div class="menu-item">
            <span>بيتزا لبناني وسط</span>
            <span>3.25</span>
            <span>كبير</span>
            <span>4.50</span>
        </div>
        <div class="menu-item">
            <span>بيتزا مارغريتا وسط</span>
            <span>2.25</span>
            <span>كبير</span>
            <span>3.75</span>
        </div>
        <div class="menu-item">
            <span>بيتزا زنجر وسط</span>
            <span>4.25</span>
            <span>كبير</span>
            <span>5.50</span>
        </div>
        <div class="menu-item">
            <span>بيتزا سوبر سبريم وسط</span>
            <span>5.50</span>
            <span>كبير</span>
            <span>7.00</span>
        </div>
    </div>
    <div class="menu-section">
        <h2>المشروبات</h2>
        <div class="menu-item">
            <span>مشروبات غازية</span>
            <span>0.50</span>
        </div>
        <div class="menu-item">
            <span>عصير</span>
            <span>0.50</span>
        </div>
        <div class="menu-item">
            <span>مياه معدنية</span>
            <span>0.35</span>
        </div>
    </div>
    <div class="menu-section">
        <h2>الطلبات الإضافية</h2>
        <div class="menu-item">
            <span>علبة صوص</span>
            <span>0.25</span>
        </div>
        <div class="menu-item">
            <span>علبة مخلل</span>
            <span>0.35</span>
        </div>
        <div class="menu-item">
            <span>بطاطا عادي</span>
            <span>1.00</span>
        </div>
        <div class="menu-item">
            <span>بطاطا ودجز</span>
            <span>1.00</span>
        </div>
        <div class="menu-item">
            <span>بطاطا كيرلي</span>
            <span>1.50</span>
        </div>
    </div>
    <div class="menu-section">
        <h2>الإضافات</h2>
        <div class="menu-item">
            <span>علبة صوص</span>
            <span>0.25</span>
        </div>
        <div class="menu-item">
            <span>علبة مخلل</span>
            <span>0.35</span>
        </div>
        <div class="menu-item">
            <span>إضافة حار 🌶️</span>
            <span>0.50</span>
        </div>
        <div class="menu-item">
            <span>علبة صوص حجم كبير</span>
            <span>1.00</span>
        </div>
        <div class="menu-item">
            <span>تبديل لبطاطا ودجز</span>
            <span>0.50</span>
        </div>
        <div class="menu-item">
            <span>تبديل البطاطا كيرلي</span>
            <span>0.50</span>
        </div>
    </div>
</body>
</html>
