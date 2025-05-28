<!DOCTYPE html>
<html lang="ja">
<head>
  <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-497PWHGTN6"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-497PWHGTN6');
</script>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>東海アートナビ - 名古屋・東海地方の美術館展覧会情報</title>
  <meta name="description" content="名古屋を中心とした東海地方の美術館の展覧会やイベント情報をまとめたサイトです。シンプルでスタイリッシュなデザインで、展覧会情報や美術館へのアクセス情報を提供します。">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.0.0/css/all.min.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;500;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Noto Sans JP', sans-serif;
      background-color: #f9f9f9;
    }
    .exhibition-card {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .exhibition-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
    }
    .museum-card {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .museum-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
    }
    .tab-content {
      display: none;
    }
    .tab-content.active {
      display: block;
    }
    .tab {
      padding: 0.5rem 1rem;
      cursor: pointer;
      border-bottom: 2px solid transparent;
    }
    .tab.active {
      border-bottom: 2px solid #3182ce;
      color: #3182ce;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header class="bg-white shadow-md">
    <div class="container mx-auto px-4 py-6 flex flex-wrap items-center justify-between">
      <div class="flex items-center">
        <h1 class="text-2xl font-bold text-gray-800">東海アートナビ</h1>
        <span class="ml-3 text-sm text-gray-600">名古屋・東海地方の美術館情報</span>
      </div>
      <nav class="hidden md:flex space-x-8">
        <a href="#featured" class="text-gray-700 hover:text-blue-600">注目の展覧会</a>
        <a href="#museums" class="text-gray-700 hover:text-blue-600">美術館一覧</a>
        <a href="#calendar" class="text-gray-700 hover:text-blue-600">イベントカレンダー</a>
        <a href="#about" class="text-gray-700 hover:text-blue-600">サイトについて</a>
      </nav>
      <div class="md:hidden">
        <button class="text-gray-700 hover:text-blue-600">
          <i class="fas fa-bars"></i>
        </button>
      </div>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-gradient-to-r from-blue-50 to-indigo-50 py-16">
    <div class="container mx-auto px-4 text-center">
      <h2 class="text-4xl md:text-5xl font-bold mb-6 text-gray-800">東海地方の美術館・展覧会情報</h2>
      <p class="text-xl text-gray-600 mb-8 max-w-3xl mx-auto">名古屋を中心に、愛知県・岐阜県・三重県・静岡県の美術館情報、展覧会、イベントを紹介します。</p>
      <div class="flex justify-center">
        <a href="#featured" class="bg-blue-600 text-white px-6 py-3 rounded-md hover:bg-blue-700 transition-colors mr-4">展覧会を探す</a>
        <a href="#museums" class="bg-gray-200 text-gray-800 px-6 py-3 rounded-md hover:bg-gray-300 transition-colors">美術館を探す</a>
      </div>
    </div>
  </section>

  <!-- Featured Exhibitions -->
  <section id="featured" class="py-16 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold mb-12 text-center text-gray-800">注目の展覧会</h2>
      
      <div class="flex flex-wrap -mx-4">
        <!-- Exhibition 1 -->
        <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
          <div class="exhibition-card bg-white rounded-lg overflow-hidden shadow-md h-full">
            <div class="h-56 bg-gray-200 relative overflow-hidden">
              <img src="https://lh3.googleusercontent.com/p/AF1QipOAt171vlOYuU8ZQ-Ksa8UGPcLXRfORdiCFILI=w138-h92-k-no" alt="ヤマザキマザック美術館" class="w-full h-full object-cover">
            </div>
            <div class="p-6">
              <div class="flex items-center mb-2">
                <span class="bg-blue-100 text-blue-800 text-xs px-2 py-1 rounded-full">開催中</span>
                <span class="ml-2 text-sm text-gray-600">2025年5月18日まで</span>
              </div>
              <h3 class="text-xl font-bold mb-2 text-gray-800">生誕120年 人間国宝 黒田辰秋 木と漆と螺鈿の旅</h3>
              <p class="text-gray-700 mb-4">豊田市美術館</p>
              <p class="text-gray-600 text-sm mb-4">漆、貝、木竹など多様な素材を生かす高い技量と造形力により、独自の足跡を工芸史に残した黒田辰秋（1904〜82）の回顧展。</p>
              <a href="#" class="text-blue-600 hover:text-blue-800">詳細を見る →</a>
            </div>
          </div>
        </div>

        <!-- Exhibition 2 -->
        <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
          <div class="exhibition-card bg-white rounded-lg overflow-hidden shadow-md h-full">
            <div class="h-56 bg-gray-200 relative overflow-hidden">
              <img src="https://lh3.googleusercontent.com/gps-cs-s/AC9h4noa-Z_Zn6oCe9_UN9pSvY3uOHnvDzCsdvSlkSzt4WLaS3_89LW2NRB2JmgwoMyAX3nbZtycF6HM4HhyUHyhBRK_wFJrR9kYHlnXmr5u2JzbFVwN2PdM81G0IhpxVYMyGPQBWJ-u=w122-h92-k-no" alt="愛知県美術館" class="w-full h-full object-cover">
            </div>
            <div class="p-6">
              <div class="flex items-center mb-2">
                <span class="bg-blue-100 text-blue-800 text-xs px-2 py-1 rounded-full">開催中</span>
                <span class="ml-2 text-sm text-gray-600">2025年6月8日まで</span>
              </div>
              <h3 class="text-xl font-bold mb-2 text-gray-800">近代日本画のトップランナー 竹内栖鳳</h3>
              <p class="text-gray-700 mb-4">愛知県美術館</p>
              <p class="text-gray-600 text-sm mb-4">「西の栖鳳・東の大観」──近代京都画壇の筆頭格として東京の横山大観と並び称された竹内栖鳳の展覧会。</p>
              <a href="#" class="text-blue-600 hover:text-blue-800">詳細を見る →</a>
            </div>
          </div>
        </div>

        <!-- Exhibition 3 -->
        <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
          <div class="exhibition-card bg-white rounded-lg overflow-hidden shadow-md h-full">
            <div class="h-56 bg-gray-200 relative overflow-hidden">
              <img src="https://lh3.googleusercontent.com/gps-cs-s/AC9h4nprCg-dqYr0poq4Egu_waOLG2RtIbFPZuYccn6Nkq6Fp9J0Ob4bVvoyPm0pcMjdQh2UL5EQfl0cYS-STViUTWGRig-kv1T9tuYQmYoCSOEw-2RBGzPPTCxpwX3RRqLR5EGQmVOC=w122-h92-k-no" alt="名古屋市美術館" class="w-full h-full object-cover">
            </div>
            <div class="p-6">
              <div class="flex items-center mb-2">
                <span class="bg-yellow-100 text-yellow-800 text-xs px-2 py-1 rounded-full">開催予定</span>
                <span class="ml-2 text-sm text-gray-600">2025年7月19日〜9月28日</span>
              </div>
              <h3 class="text-xl font-bold mb-2 text-gray-800">特集 匹亞会結成70年 結成前夜</h3>
              <p class="text-gray-700 mb-4">名古屋市美術館</p>
              <p class="text-gray-600 text-sm mb-4">特集 匹亞会結成70年の記念展覧会。名古屋で発足した前衛芸術団体「匹亞会」の作品を紹介。</p>
              <a href="#" class="text-blue-600 hover:text-blue-800">詳細を見る →</a>
            </div>
          </div>
        </div>

        <!-- Exhibition 4 -->
        <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
          <div class="exhibition-card bg-white rounded-lg overflow-hidden shadow-md h-full">
            <div class="h-56 bg-gray-200 relative overflow-hidden">
              <img src="https://lh3.googleusercontent.com/p/AF1QipO50PYbmqtDjRgeFXydRhoaVfvh_Ch0ChhHjEJ4=w138-h92-k-no" alt="徳川美術館" class="w-full h-full object-cover">
            </div>
            <div class="p-6">
              <div class="flex items-center mb-2">
                <span class="bg-yellow-100 text-yellow-800 text-xs px-2 py-1 rounded-full">開催予定</span>
                <span class="ml-2 text-sm text-gray-600">2025年6月1日〜7月15日</span>
              </div>
              <h3 class="text-xl font-bold mb-2 text-gray-800">徳川家の名宝展</h3>
              <p class="text-gray-700 mb-4">徳川美術館</p>
              <p class="text-gray-600 text-sm mb-4">徳川将軍家に伝わる貴重な美術品や歴史資料を展示。国宝「源氏物語絵巻」などの名品を鑑賞できる特別展。</p>
              <a href="#" class="text-blue-600 hover:text-blue-800">詳細を見る →</a>
            </div>
          </div>
        </div>

        <!-- Exhibition 5 -->
        <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
          <div class="exhibition-card bg-white rounded-lg overflow-hidden shadow-md h-full">
            <div class="h-56 bg-gray-200 relative overflow-hidden">
              <img src="https://lh3.googleusercontent.com/gps-cs-s/AC9h4noaHzDrX4PcZ5TJyqWnRNI6xEK8MsmkJP3HXf4OA7VaYiu-5jrSu1p4VXZu_P-P2LTGUp4mvEZ6usdIJKzg05STe1DSkh-CvO0o7dyEMu1OIzg8WJNsStVTyOBOGBVmMSAd4Sk=w129-h86-k-no" alt="豊田市美術館" class="w-full h-full object-cover">
            </div>
            <div class="p-6">
              <div class="flex items-center mb-2">
                <span class="bg-yellow-100 text-yellow-800 text-xs px-2 py-1 rounded-full">開催予定</span>
                <span class="ml-2 text-sm text-gray-600">2025年6月21日〜9月15日</span>
              </div>
              <h3 class="text-xl font-bold mb-2 text-gray-800">モネ－睡蓮のとき</h3>
              <p class="text-gray-700 mb-4">豊田市美術館</p>
              <p class="text-gray-600 text-sm mb-4">印象派を代表する画家クロード・モネの代表作「睡蓮」シリーズを中心に、その芸術の変遷を辿る展覧会。</p>
              <a href="#" class="text-blue-600 hover:text-blue-800">詳細を見る →</a>
            </div>
          </div>
        </div>

        <!-- Exhibition 6 -->
        <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
          <div class="exhibition-card bg-white rounded-lg overflow-hidden shadow-md h-full">
            <div class="h-56 bg-gray-200 relative overflow-hidden">
              <img src="https://lh3.googleusercontent.com/p/AF1QipNwVYr-EoPLCwNDIK76KaDKhbRt_dbADFKZ0ZX_=w116-h92-k-no" alt="古川美術館" class="w-full h-full object-cover">
            </div>
            <div class="p-6">
              <div class="flex items-center mb-2">
                <span class="bg-blue-100 text-blue-800 text-xs px-2 py-1 rounded-full">開催中</span>
                <span class="ml-2 text-sm text-gray-600">2025年5月25日まで</span>
              </div>
              <h3 class="text-xl font-bold mb-2 text-gray-800">日本画名品展 ─四季の彩り─</h3>
              <p class="text-gray-700 mb-4">古川美術館</p>
              <p class="text-gray-600 text-sm mb-4">日本の四季を題材にした名作日本画を展示。日本美術特有の繊細な表現と季節感を堪能できる展覧会。</p>
              <a href="#" class="text-blue-600 hover:text-blue-800">詳細を見る →</a>
            </div>
          </div>
        </div>
      </div>

      <div class="text-center mt-8">
        <a href="#" class="inline-block bg-blue-600 text-white px-6 py-3 rounded-md hover:bg-blue-700 transition-colors">すべての展覧会を見る</a>
      </div>
    </div>
  </section>

  <!-- Museum Directory -->
  <section id="museums" class="py-16 bg-gray-50">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold mb-12 text-center text-gray-800">美術館ディレクトリ</h2>

      <div class="flex flex-wrap justify-center mb-8">
        <div class="tab active" data-tab="nagoya">名古屋市</div>
        <div class="tab" data-tab="aichi">愛知県</div>
        <div class="tab" data-tab="mie">三重県</div>
        <div class="tab" data-tab="gifu">岐阜県</div>
        <div class="tab" data-tab="shizuoka">静岡県</div>
      </div>

      <!-- 名古屋市の美術館 -->
      <div id="nagoya-tab" class="tab-content active">
        <div class="flex flex-wrap -mx-4">
          <!-- Museum 1 -->
          <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
            <div class="museum-card bg-white rounded-lg overflow-hidden shadow-md h-full">
              <div class="h-48 bg-gray-200 relative overflow-hidden">
                <img src="https://lh3.googleusercontent.com/gps-cs-s/AC9h4nprCg-dqYr0poq4Egu_waOLG2RtIbFPZuYccn6Nkq6Fp9J0Ob4bVvoyPm0pcMjdQh2UL5EQfl0cYS-STViUTWGRig-kv1T9tuYQmYoCSOEw-2RBGzPPTCxpwX3RRqLR5EGQmVOC=w122-h92-k-no" alt="名古屋市美術館" class="w-full h-full object-cover">
              </div>
              <div class="p-6">
                <h3 class="text-xl font-bold mb-2 text-gray-800">名古屋市美術館</h3>
                <p class="text-gray-600 text-sm mb-4">エコール・ド・パリやメキシコ・ルネサンス、郷土の美術、現代美術の作品を中心に収蔵しています。</p>
                <div class="mb-4">
                  <div class="flex items-center mb-2">
                    <i class="fas fa-map-marker-alt text-red-500 mr-2"></i>
                    <span class="text-sm text-gray-700">名古屋市中区栄2-17-25 芸術と科学の杜・白川公園内</span>
                  </div>
                  <div class="flex items-center mb-2">
                    <i class="fas fa-phone text-blue-500 mr-2"></i>
                    <span class="text-sm text-gray-700">052-212-0001</span>
                  </div>
                  <div class="flex items-center mb-2">
                    <i class="fas fa-clock text-green-500 mr-2"></i>
                    <span class="text-sm text-gray-700">9:30～17:00（金曜は20:00まで）、月曜休館</span>
                  </div>
                </div>
                <div class="flex justify-between">
                  <a href="https://art-museum.city.nagoya.jp/" target="_blank" class="text-blue-600 hover:text-blue-800 text-sm">公式サイト</a>
                  <a href="#" class="text-blue-600 hover:text-blue-800 text-sm">地図で見る</a>
                </div>
              </div>
            </div>
          </div>

          <!-- Museum 2 -->
          <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
            <div class="museum-card bg-white rounded-lg overflow-hidden shadow-md h-full">
              <div class="h-48 bg-gray-200 relative overflow-hidden">
                <img src="https://lh3.googleusercontent.com/gps-cs-s/AC9h4noa-Z_Zn6oCe9_UN9pSvY3uOHnvDzCsdvSlkSzt4WLaS3_89LW2NRB2JmgwoMyAX3nbZtycF6HM4HhyUHyhBRK_wFJrR9kYHlnXmr5u2JzbFVwN2PdM81G0IhpxVYMyGPQBWJ-u=w122-h92-k-no" alt="愛知県美術館" class="w-full h-full object-cover">
              </div>
              <div class="p-6">
                <h3 class="text-xl font-bold mb-2 text-gray-800">愛知県美術館</h3>
                <p class="text-gray-600 text-sm mb-4">主にピカソ、マティスなどの海外作家と日本人作家の近現代美術作品を展示しています。</p>
                <div class="mb-4">
                  <div class="flex items-center mb-2">
                    <i class="fas fa-map-marker-alt text-red-500 mr-2"></i>
                    <span class="text-sm text-gray-700">名古屋市東区東桜1-13-2 愛知芸術文化センター内</span>
                  </div>
                  <div class="flex items-center mb-2">
                    <i class="fas fa-phone text-blue-500 mr-2"></i>
                    <span class="text-sm text-gray-700">052-971-5511</span>
                  </div>
                  <div class="flex items-center mb-2">
                    <i class="fas fa-clock text-green-500 mr-2"></i>
                    <span class="text-sm text-gray-700">10:00～18:00（金曜は20:00まで）、月曜休館</span>
                  </div>
                </div>
                <div class="flex justify-between">
                  <a href="https://www-art.aac.pref.aichi.jp/" target="_blank" class="text-blue-600 hover:text-blue-800 text-sm">公式サイト</a>
                  <a href="#" class="text-blue-600 hover:text-blue-800 text-sm">地図で見る</a>
                </div>
              </div>
            </div>
          </div>

          <!-- Museum 3 -->
          <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
            <div class="museum-card bg-white rounded-lg overflow-hidden shadow-md h-full">
              <div class="h-48 bg-gray-200 relative overflow-hidden">
                <img src="https://lh3.googleusercontent.com/p/AF1QipO50PYbmqtDjRgeFXydRhoaVfvh_Ch0ChhHjEJ4=w138-h92-k-no" alt="徳川美術館" class="w-full h-full object-cover">
              </div>
              <div class="p-6">
                <h3 class="text-xl font-bold mb-2 text-gray-800">徳川美術館</h3>
                <p class="text-gray-600 text-sm mb-4">国宝「源氏物語絵巻」をはじめ、徳川将軍家に伝わる美術品や歴史資料を展示しています。</p>
                <div class="mb-4">
                  <div class="flex items-center mb-2">
                    <i class="fas fa-map-marker-alt text-red-500 mr-2"></i>
                    <span class="text-sm text-gray-700">名古屋市東区徳川町1017</span>
                  </div>
                  <div class="flex items-center mb-2">
                    <i class="fas fa-phone text-blue-500 mr-2"></i>
                    <span class="text-sm text-gray-700">052-935-6262</span>
                  </div>
                  <div class="flex items-center mb-2">
                    <i class="fas fa-clock text-green-500 mr-2"></i>
                    <span class="text-sm text-gray-700">10:00～17:00、月曜休館</span>
                  </div>
                </div>
                <div class="flex justify-between">
                  <a href="https://www.tokugawa-art-museum.jp/" target="_blank" class="text-blue-600 hover:text-blue-800 text-sm">公式サイト</a>
                  <a href="#" class="text-blue-600 hover:text-blue-800 text-sm">地図で見る</a>
                </div>
              </div>
            </div>
          </div>

          <!-- Museum 4 -->
          <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
            <div class="museum-card bg-white rounded-lg overflow-hidden shadow-md h-full">
              <div class="h-48 bg-gray-200 relative overflow-hidden">
                <img src="https://lh3.googleusercontent.com/p/AF1QipOAt171vlOYuU8ZQ-Ksa8UGPcLXRfORdiCFILI=w138-h92-k-no" alt="ヤマザキマザック美術館" class="w-full h-full object-cover">
              </div>
              <div class="p-6">
                <h3 class="text-xl font-bold mb-2 text-gray-800">ヤマザキマザック美術館</h3>
                <p class="text-gray-600 text-sm mb-4">18世紀～20世紀のフランス絵画や家具を中心に展示した美術館です。</p>
                <div class="mb-4">
                  <div class="flex items-center mb-2">
                    <i class="fas fa-map-marker-alt text-red-500 mr-2"></i>
                    <span class="text-sm text-gray-700">名古屋市東区葵1-19-30</span>
                  </div>
                  <div class="flex items-center mb-2">
                    <i class="fas fa-phone text-blue-500 mr-2"></i>
                    <span class="text-sm text-gray-700">052-937-3737</span>
                  </div>
                  <div class="flex items-center mb-2">
                    <i class="fas fa-clock text-green-500 mr-2"></i>
                    <span class="text-sm text-gray-700">10:00～17:00、月曜休館</span>
                  </div>
                </div>
                <div class="flex justify-between">
                  <a href="https://www.mazak-art.com/" target="_blank" class="text-blue-600 hover:text-blue-800 text-sm">公式サイト</a>
                  <a href="#" class="text-blue-600 hover:text-blue-800 text-sm">地図で見る</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- 愛知県の美術館 -->
      <div id="aichi-tab" class="tab-content">
        <div class="flex flex-wrap -mx-4">
          <!-- Museum 5 -->
          <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
            <div class="museum-card bg-white rounded-lg overflow-hidden shadow-md h-full">
              <div class="h-48 bg-gray-200 relative overflow-hidden">
                <img src="https://lh3.googleusercontent.com/gps-cs-s/AC9h4noaHzDrX4PcZ5TJyqWnRNI6xEK8MsmkJP3HXf4OA7VaYiu-5jrSu1p4VXZu_P-P2LTGUp4mvEZ6usdIJKzg05STe1DSkh-CvO0o7dyEMu1OIzg8WJNsStVTyOBOGBVmMSAd4Sk=w129-h86-k-no" alt="豊田市美術館" class="w-full h-full object-cover">
              </div>
              <div class="p-6">
                <h3 class="text-xl font-bold mb-2 text-gray-800">豊田市美術館</h3>
                <p class="text-gray-600 text-sm mb-4">谷口吉生設計の建築と現代美術の作品が融合した美術館です。</p>
                <div class="mb-4">
                  <div class="flex items-center mb-2">
                    <i class="fas fa-map-marker-alt text-red-500 mr-2"></i>
                    <span class="text-sm text-gray-700">豊田市小坂本町8-5-1</span>
                  </div>
                  <div class="flex items-center mb-2">
                    <i class="fas fa-phone text-blue-500 mr-2"></i>
                    <span class="text-sm text-gray-700">0565-34-6610</span>
                  </div>
                  <div class="flex items-center mb-2">
                    <i class="fas fa-clock text-green-500 mr-2"></i>
                    <span class="text-sm text-gray-700">10:00～17:30、月曜休館</span>
                  </div>
                </div>
                <div class="flex justify-between">
                  <a href="https://www.museum.toyota.aichi.jp/" target="_blank" class="text-blue-600 hover:text-blue-800 text-sm">公式サイト</a>
                  <a href="#" class="text-blue-600 hover:text-blue-800 text-sm">地図で見る</a>
                </div>
              </div>
            </div>
          </div>

          <!-- Museum 6 -->
          <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8">
            <div class="museum-card bg-white rounded-lg overflow-hidden shadow-md h-full">
              <div class="h-48 bg-gray-200 relative overflow-hidden">
                <img src="https://lh3.googleusercontent.com/p/AF1QipNwVYr-EoPLCwNDIK76KaDKhbRt_dbADFKZ0ZX_=w116-h92-k-no" alt="古川美術館" class="w-full h-full object-cover">
              </div>
              <div class="p-6">
                <h3 class="text-xl font-bold mb-2 text-gray-800">古川美術館</h3>
                <p class="text-gray-600 text-sm mb-4">日本画や茶道具などの東洋美術の名品を収蔵・展示しています。</p>
                <div class="mb-4">
                  <div class="flex items-center mb-2">
                    <i class="fas fa-map-marker-alt text-red-500 mr-2"></i>
                    <span class="text-sm text-gray-700">名古屋市千種区池下町2-50</span>
                  </div>
                  <div class="flex items-center mb-2">
                    <i class="fas fa-phone text-blue-500 mr-2"></i>
                    <span class="text-sm text-gray-700">052-763-1991</span>
                  </div>
                  <div class="flex items-center mb-2">
                    <i class="fas fa-clock text-green-500 mr-2"></i>
                    <span class="text-sm text-gray-700">10:00～17:00、月曜休館</span>
                  </div>
                </div>
                <div class="flex justify-between">
                  <a href="http://www.furukawa-museum.or.jp/" target="_blank" class="text-blue-600 hover:text-blue-800 text-sm">公式サイト</a>
                  <a href="#" class="text-blue-600 hover:text-blue-800 text-sm">地図で見る</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- 三重県の美術館 -->
      <div id="mie-tab" class="tab-content">
        <div class="text-center py-8">
          <p class="text-gray-600">現在、三重県の美術館情報を準備中です。</p>
        </div>
      </div>

      <!-- 岐阜県の美術館 -->
      <div id="gifu-tab" class="tab-content">
        <div class="text-center py-8">
          <p class="text-gray-600">現在、岐阜県の美術館情報を準備中です。</p>
        </div>
      </div>

      <!-- 静岡県の美術館 -->
      <div id="shizuoka-tab" class="tab-content">
        <div class="text-center py-8">
          <p class="text-gray-600">現在、静岡県の美術館情報を準備中です。</p>
        </div>
      </div>

      <div class="mt-12 p-8 bg-white rounded-lg shadow-md">
        <h3 class="text-xl font-bold mb-4 text-center text-gray-800">Google マップで美術館を探す</h3>
        <div class="bg-gray-200 rounded-lg h-96 w-full flex items-center justify-center">
          <p class="text-gray-600">ここにGoogleマップが表示されます。</p>
          <p class="text-gray-500 text-sm">（マップ連携機能は実装中です）</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Calendar Section -->
  <section id="calendar" class="py-16 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold mb-12 text-center text-gray-800">イベントカレンダー</h2>

      <div class="flex flex-col lg:flex-row">
        <!-- Month Navigation -->
        <div class="w-full lg:w-1/4 mb-8 lg:mb-0 lg:pr-8">
          <div class="bg-white rounded-lg shadow-md p-6">
            <h3 class="text-lg font-bold mb-4 text-gray-800">2025年</h3>
            <ul class="space-y-2">
              <li><a href="#" class="text-gray-700 hover:text-blue-600 flex items-center"><span class="w-4 h-4 bg-blue-500 rounded-full mr-2"></span>1月</a></li>
              <li><a href="#" class="text-gray-700 hover:text-blue-600 flex items-center"><span class="w-4 h-4 bg-blue-500 rounded-full mr-2"></span>2月</a></li>
              <li><a href="#" class="text-gray-700 hover:text-blue-600 flex items-center"><span class="w-4 h-4 bg-blue-500 rounded-full mr-2"></span>3月</a></li>
              <li><a href="#" class="text-gray-700 hover:text-blue-600 flex items-center"><span class="w-4 h-4 bg-blue-500 rounded-full mr-2"></span>4月</a></li>
              <li><a href="#" class="text-gray-700 hover:text-blue-600 flex items-center"><span class="w-4 h-4 bg-green-500 rounded-full mr-2"></span>5月 (今月)</a></li>
              <li><a href="#" class="text-gray-700 hover:text-blue-600 flex items-center"><span class="w-4 h-4 bg-blue-500 rounded-full mr-2"></span>6月</a></li>
              <li><a href="#" class="text-gray-700 hover:text-blue-600 flex items-center"><span class="w-4 h-4 bg-blue-500 rounded-full mr-2"></span>7月</a></li>
              <li><a href="#" class="text-gray-700 hover:text-blue-600 flex items-center"><span class="w-4 h-4 bg-blue-500 rounded-full mr-2"></span>8月</a></li>
              <li><a href="#" class="text-gray-700 hover:text-blue-600 flex items-center"><span class="w-4 h-4 bg-blue-500 rounded-full mr-2"></span>9月</a></li>
              <li><a href="#" class="text-gray-700 hover:text-blue-600 flex items-center"><span class="w-4 h-4 bg-blue-500 rounded-full mr-2"></span>10月</a></li>
              <li><a href="#" class="text-gray-700 hover:text-blue-600 flex items-center"><span class="w-4 h-4 bg-blue-500 rounded-full mr-2"></span>11月</a></li>
              <li><a href="#" class="text-gray-700 hover:text-blue-600 flex items-center"><span class="w-4 h-4 bg-blue-500 rounded-full mr-2"></span>12月</a></li>
            </ul>
          </div>
        </div>

        <!-- Calendar Events -->
        <div class="w-full lg:w-3/4">
          <div class="bg-white rounded-lg shadow-md p-6">
            <div class="flex items-center justify-between mb-6">
              <h3 class="text-xl font-bold text-gray-800">2025年5月</h3>
              <div class="flex space-x-2">
                <button class="p-2 rounded-full bg-gray-200 hover:bg-gray-300">
                  <i class="fas fa-chevron-left text-gray-600"></i>
                </button>
                <button class="p-2 rounded-full bg-gray-200 hover:bg-gray-300">
                  <i class="fas fa-chevron-right text-gray-600"></i>
                </button>
              </div>
            </div>

            <!-- Calendar Events List -->
            <div class="space-y-4">
              <!-- Event 1 -->
              <div class="border-l-4 border-blue-500 pl-4 py-2">
                <div class="flex items-center">
                  <div class="bg-blue-100 text-blue-800 text-xs px-2 py-1 rounded-full mr-2">開催中</div>
                  <p class="text-gray-600 text-sm">～5月18日</p>
                </div>
                <h4 class="font-bold text-gray-800 mt-1">生誕120年 人間国宝 黒田辰秋 木と漆と螺鈿の旅</h4>
                <p class="text-gray-700 text-sm">豊田市美術館</p>
              </div>

              <!-- Event 2 -->
              <div class="border-l-4 border-blue-500 pl-4 py-2">
                <div class="flex items-center">
                  <div class="bg-blue-100 text-blue-800 text-xs px-2 py-1 rounded-full mr-2">開催中</div>
                  <p class="text-gray-600 text-sm">～6月8日</p>
                </div>
                <h4 class="font-bold text-gray-800 mt-1">近代日本画のトップランナー 竹内栖鳳</h4>
                <p class="text-gray-700 text-sm">愛知県美術館</p>
              </div>

              <!-- Event 3 -->
              <div class="border-l-4 border-blue-500 pl-4 py-2">
                <div class="flex items-center">
                  <div class="bg-blue-100 text-blue-800 text-xs px-2 py-1 rounded-full mr-2">開催中</div>
                  <p class="text-gray-600 text-sm">～5月25日</p>
                </div>
                <h4 class="font-bold text-gray-800 mt-1">日本画名品展 ─四季の彩り─</h4>
                <p class="text-gray-700 text-sm">古川美術館</p>
              </div>

              <!-- Event 4 -->
              <div class="border-l-4 border-yellow-500 pl-4 py-2">
                <div class="flex items-center">
                  <div class="bg-yellow-100 text-yellow-800 text-xs px-2 py-1 rounded-full mr-2">開催予定</div>
                  <p class="text-gray-600 text-sm">5月10日～5月17日</p>
                </div>
                <h4 class="font-bold text-gray-800 mt-1">北海道八雲町</h4>
                <p class="text-gray-700 text-sm">Hase（ハーゼ）</p>
              </div>

              <!-- Event 5 -->
              <div class="border-l-4 border-yellow-500 pl-4 py-2">
                <div class="flex items-center">
                  <div class="bg-yellow-100 text-yellow-800 text-xs px-2 py-1 rounded-full mr-2">開催予定</div>
                  <p class="text-gray-600 text-sm">5月25日～6月30日</p>
                </div>
                <h4 class="font-bold text-gray-800 mt-1">まるまる まるごと まつおかとおる</h4>
                <p class="text-gray-700 text-sm">名古屋市美術館</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-16 bg-gray-50">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold mb-8 text-center text-gray-800">サイトについて</h2>
      
      <div class="max-w-3xl mx-auto bg-white rounded-lg shadow-md p-8">
        <h3 class="text-xl font-bold mb-4 text-gray-800">東海アートナビについて</h3>
        <p class="text-gray-600 mb-6">「東海アートナビ」は、名古屋を中心とした東海地方（愛知県、岐阜県、三重県、静岡県）の美術館の展覧会やイベント情報をまとめたサイトです。美術館や展覧会の情報をシンプルでわかりやすく提供することで、皆様の文化芸術活動のお手伝いをしたいと考えています。</p>
        
        <h3 class="text-xl font-bold mb-4 text-gray-800">掲載内容</h3>
        <ul class="list-disc pl-6 text-gray-600 mb-6">
          <li>各美術館の基本情報（住所、開館時間、休館日など）</li>
          <li>開催中・開催予定の展覧会情報</li>
          <li>展覧会カレンダー</li>
          <li>Google マップと連携した美術館マップ</li>
          <li>各展覧会の関連リンク集</li>
        </ul>
        
        <h3 class="text-xl font-bold mb-4 text-gray-800">更新頻度</h3>
        <p class="text-gray-600 mb-6">展覧会情報は各美術館の公式発表に基づき、随時更新しています。最新の情報については、各美術館の公式サイトもご確認ください。</p>
        
        <h3 class="text-xl font-bold mb-4 text-gray-800">お問い合わせ</h3>
        <p class="text-gray-600">展覧会情報の追加や修正のご要望、その他お問い合わせは以下のメールアドレスまでお願いします。</p>
        <p class="text-blue-600 font-medium">info@tokai-art-navi.jp</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 py-10">
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap items-center justify-between">
        <div class="w-full md:w-1/3 mb-6 md:mb-0">
          <h2 class="text-xl font-bold text-white mb-4">東海アートナビ</h2>
          <p class="text-gray-400">名古屋を中心とした東海地方の美術館・展覧会情報サイト</p>
        </div>
        
        <div class="w-full md:w-1/3 mb-6 md:mb-0">
          <h3 class="text-lg font-bold text-white mb-4">リンク</h3>
          <ul class="space-y-2">
            <li><a href="#featured" class="text-gray-400 hover:text-white">注目の展覧会</a></li>
            <li><a href="#museums" class="text-gray-400 hover:text-white">美術館一覧</a></li>
            <li><a href="#calendar" class="text-gray-400 hover:text-white">イベントカレンダー</a></li>
            <li><a href="#about" class="text-gray-400 hover:text-white">サイトについて</a></li>
          </ul>
        </div>
        
        <div class="w-full md:w-1/3">
          <h3 class="text-lg font-bold text-white mb-4">フォローする</h3>
          <div class="flex space-x-4">
            <a href="#" class="text-gray-400 hover:text-white">
              <i class="fab fa-twitter text-xl"></i>
            </a>
            <a href="#" class="text-gray-400 hover:text-white">
              <i class="fab fa-facebook text-xl"></i>
            </a>
            <a href="#" class="text-gray-400 hover:text-white">
              <i class="fab fa-instagram text-xl"></i>
            </a>
          </div>
        </div>
      </div>
      
      <div class="border-t border-gray-700 mt-8 pt-8 text-center">
        <p class="text-gray-400">&copy; 2025 東海アートナビ All Rights Reserved.</p>
      </div>
    </div>
  </footer>

  <script>
    // Tab switching functionality
    document.addEventListener('DOMContentLoaded', function() {
      const tabs = document.querySelectorAll('.tab');
      tabs.forEach(tab => {
        tab.addEventListener('click', function() {
          // Remove active class from all tabs
          tabs.forEach(t => t.classList.remove('active'));
          
          // Add active class to clicked tab
          this.classList.add('active');
          
          // Hide all tab content
          const tabContents = document.querySelectorAll('.tab-content');
          tabContents.forEach(content => {
            content.classList.remove('active');
          });
          
          // Show the corresponding tab content
          const tabId = this.getAttribute('data-tab');
          document.getElementById(tabId + '-tab').classList.add('active');
        });
      });
    });
  </script>
</body>
</html>
reCAPTCHA サービスに接続できませんでした。インターネット接続を確認して、reCAPTCHA を再読み込みしてください。
