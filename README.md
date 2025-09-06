<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GV Nguyễn Thu Huyền </title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            color: #1f2937;
        }
        .hero-section {
            background-image: linear-gradient(to right, #60a5fa, #3b82f6);
            color: white;
            padding: 4rem 1rem;
            text-align: center;
        }
        .subject-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .subject-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
    </style>
</head>
<body class="bg-gray-100">

    <!-- Thanh điều hướng -->
    <nav class="bg-white shadow-lg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <a href="#" class="text-2xl font-bold text-blue-600">GV Nguyễn Thu Huyền</a>
                </div>
                <div class="flex items-center space-x-4">
                    <a href="#mon-hoc" class="text-gray-600 hover:text-blue-600 font-medium">Môn học</a>
                    <a href="#" class="text-gray-600 hover:text-blue-600 font-medium">Thông tin</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Phần giới thiệu -->
    <header class="hero-section rounded-b-3xl">
        <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold mb-4">
            Chào mừng đến với thư viện học liệu
        </h1>
        <p class="text-lg sm:text-xl lg:text-2xl font-light mb-8">
            Nơi kiến thức được sắp xếp khoa học và dễ dàng tiếp cận
        </p>
        <button class="bg-white text-blue-600 font-bold py-3 px-8 rounded-full shadow-lg hover:bg-gray-100 transition duration-300">
            Khám phá ngay
        </button>
    </header>

    <!-- Khu vực các môn học -->
    <main id="mon-hoc" class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-bold text-center mb-10 text-gray-800">Các môn học</h2>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Thẻ môn Toán 6A1 -->
            <div class="subject-card bg-white p-6 rounded-2xl shadow-md border-b-4 border-blue-500">
                <h3 class="text-xl font-semibold mb-2 text-blue-700">Toán 6A1</h3>
                <p class="text-gray-600 mb-4">Tài liệu học tập và bài giảng dành cho lớp 6A1.</p>
                <div class="mt-4 border-t pt-4">
                    <h4 class="text-lg font-semibold text-blue-600 mb-2">Bài học</h4>
                    <a href="https://drive.google.com/file/d/1QPK7LY8d86CT1Qihj0xucbitPwyHVifT/view?usp=sharing" target="_blank" class="block p-4 mb-2 bg-blue-50 rounded-lg hover:bg-blue-100 transition duration-300">
                        <p class="font-medium text-blue-800">Tuần 1</p>
                        <p class="text-sm text-gray-500">Tải file BTVN Tuần 1.</p>
                        <a href="https://drive.google.com/file/d/1JCXJ_jftVy6IgVC5vioqFMG4fKiKPBsR/view?usp=sharing" target="_blank" class="block p-4 mb-2 bg-blue-50 rounded-lg hover:bg-blue-100 transition duration-300">
                        <p class="font-medium text-blue-800">Tuần 2</p>
                        <p class="text-sm text-gray-500">Tải file BTVN Tuần 2.</p>
            </a>
                </div>
                <a href="#" class="inline-block mt-4 text-gray-500 font-semibold hover:underline">Xem thêm tài liệu &rarr;</a>
            </div>
                        
            <!-- Thẻ môn Toán 8A1 -->
            <div class="subject-card bg-white p-6 rounded-2xl shadow-md border-b-4 border-blue-500">
                <h3 class="text-xl font-semibold mb-2 text-blue-700">Toán 8A1</h3>
                <p class="text-gray-600 mb-4">Tài liệu học tập và bài giảng dành cho lớp 8A1.</p>
                <div class="mt-4 border-t pt-4">
                    <h4 class="text-lg font-semibold text-blue-600 mb-2">Bài học</h4>
                    <a href="https://drive.google.com/file/d/1zLL_LPpf6F949z37MdiUqFTDtoA82YPV/view?usp=sharing" target="_blank" class="block p-4 mb-2 bg-blue-50 rounded-lg hover:bg-blue-100 transition duration-300">
                        <p class="font-medium text-blue-800">Tuần 1</p>
                        <p class="text-sm text-gray-500">Tải file BTVN Tuần 1.</p>
                        <a href="https://drive.google.com/file/d/1FF1bMyO56h8Rl-tlZVIru8hv9IyHw28H/view?usp=sharing" target="_blank" class="block p-4 mb-2 bg-blue-50 rounded-lg hover:bg-blue-100 transition duration-300">
                        <p class="font-medium text-blue-800">Tuần 2</p>
                        <p class="text-sm text-gray-500">Tải file BTVN Tuần 2.</p>
            </a>
                </div>
                <a href="#" class="inline-block mt-4 text-gray-500 font-semibold hover:underline">Xem thêm tài liệu &rarr;</a>
            </div>
                        
           <!-- Thẻ môn Tin học 6 -->
            <div class="subject-card bg-white p-6 rounded-2xl shadow-md border-b-4 border-gray-500">
                <h3 class="text-xl font-semibold mb-2 text-gray-700">Tin học 6</h3>
                <p class="text-gray-600 mb-4">Tài liệu học tập và bài giảng cho lớp 6.</p>
                <div class="mt-4 border-t pt-4">
                    <h4 class="text-lg font-semibold text-gray-600 mb-2">Bài học</h4>
                    <a href="https://drive.google.com/file/d/1hcNOhH8-dqEj78a3sKvwtOnXhwSMO5dS/view?usp=sharing" target="_blank" class="block p-4 mb-2 bg-gray-50 rounded-lg hover:bg-gray-100 transition duration-300">
                        <p class="font-medium text-gray-800">Bài tập Tin học 6</p>
                        <p class="text-sm text-gray-500">Bài tập.</p>
                    </a>
                </div>
                <a href="#" class="inline-block mt-4 text-gray-500 font-semibold hover:underline">Xem thêm tài liệu &rarr;</a>
            </div>

            <!-- Thẻ môn Tin học 7 -->
            <div class="subject-card bg-white p-6 rounded-2xl shadow-md border-b-4 border-gray-500">
                <h3 class="text-xl font-semibold mb-2 text-gray-700">Tin học 7</h3>
                <p class="text-gray-600 mb-4">Tài liệu học tập và bài giảng cho lớp 7.</p>
                <div class="mt-4 border-t pt-4">
                    <h4 class="text-lg font-semibold text-gray-600 mb-2">Bài học</h4>
                    <a href="https://drive.google.com/file/d/1JK6Axuxx3UVZK690FBaAom88qGVBHFNV/view?usp=sharing" target="_blank" class="block p-4 mb-2 bg-gray-50 rounded-lg hover:bg-gray-100 transition duration-300">
                        <p class="font-medium text-gray-800">Bài tập Tin học 7</p>
                        <p class="text-sm text-gray-500">Bài tập.</p>
                    </a>
                </div>
                <a href="#" class="inline-block mt-4 text-gray-500 font-semibold hover:underline">Xem thêm tài liệu &rarr;</a>
            </div>

            <!-- Thẻ môn Tin học 8 -->
            <div class="subject-card bg-white p-6 rounded-2xl shadow-md border-b-4 border-gray-500">
                <h3 class="text-xl font-semibold mb-2 text-gray-700">Tin học 8</h3>
                <p class="text-gray-600 mb-4">Tài liệu học tập và bài giảng cho lớp 8.</p>
                <div class="mt-4 border-t pt-4">
                    <h4 class="text-lg font-semibold text-gray-600 mb-2">Bài học</h4>
                    <a href="https://drive.google.com/file/d/1wWCn5fTpix6lwFP7Q-bJUImp99fiuNHY/view?usp=sharing" target="_blank" class="block p-4 mb-2 bg-gray-50 rounded-lg hover:bg-gray-100 transition duration-300">
                        <p class="font-medium text-gray-800">Bài tập Tin học 8</p>
                        <p class="text-sm text-gray-500">Bài tập.</p>
                    </a>
                </div>
                <a href="#" class="inline-block mt-4 text-gray-500 font-semibold hover:underline">Xem thêm tài liệu &rarr;</a>
            </div>
           
        </div>
    </main>

    <!-- Chân trang -->
    <footer class="bg-gray-800 text-white py-8 mt-12 rounded-t-3xl">
        <div class="max-w-7xl mx-auto text-center">
            <p>&copy; 2024 GV NGUYỄN THU HUYỀN - TRƯỜNG THCS DUYÊN HÀ. Tất cả bản quyền thuộc về nhà phát triển.</p>
        </div>
    </footer>

</body>
</html>
