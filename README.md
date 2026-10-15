# ghesse-khane-enghelab
سایت قصه‌خانه انقلاب؛ مجموعه‌ای از داستان‌های جذاب و آموزنده
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="description" content="داستان‌های نوجوانانه، ایرانی، آموزنده و الهام‌بخش">
<title>قصه‌خانه انقلاب | سید یوسف حسینی‌زاده</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  background: #f7f8f2;
  color: #20352a;
  font-family: Tahoma, Arial, sans-serif;
  line-height: 2;
}

header {
  background: linear-gradient(135deg, #073c29, #137548);
  color: white;
  text-align: center;
  padding: 44px 16px;
}

header h1 {
  font-size: clamp(28px, 5vw, 42px);
  margin: 0;
}

header p {
  color: #e0eee4;
}

nav {
  background: white;
  padding: 13px;
  text-align: center;
  box-shadow: 0 2px 8px #0001;
}

nav a {
  color: #12663e;
  text-decoration: none;
  margin: 0 12px;
  font-weight: bold;
}

main {
  max-width: 1050px;
  margin: 28px auto;
  padding: 0 16px;
}

h2 {
  color: #12663e;
}

#search {
  width: 100%;
  padding: 14px;
  border: 1px solid #ccd8cd;
  border-radius: 12px;
  font-size: 16px;
}

.filters {
  display: flex;
  gap: 8px;
  flex-wrap: wrap;
  margin: 16px 0;
}

.filters button,
.read {
  cursor: pointer;
  border: 0;
  border-radius: 9px;
  padding: 9px 14px;
  background: #146c43;
  color: white;
  font-size: 14px;
}

.filters button.active {
  background: #d5ad51;
  color: #222;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 17px;
}

.card {
  background: white;
  border: 1px solid #e1e8df;
  border-radius: 16px;
  padding: 20px;
  box-shadow: 0 5px 18px #183b2010;
}

.card h3 {
  color: #12663e;
  margin-bottom: 4px;
}

.card p {
  color: #5d6b61;
}

.author {
  border-top: 1px solid #e3e8e
