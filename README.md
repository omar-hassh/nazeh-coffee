<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مكان الكراج - أفضل مكان للعب الورق</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #34495e;
            --accent-color: #e74c3c;
            --text-light: #ecf0f1;
            --text-dark: #2c3e50;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --transition: all 0.3s ease;
        }

        body {
            font-family: 'Cairo', sans-serif;
            direction: rtl;
            line-height: 1.6;
            color: var(--text-dark);
        }

        .navbar {
            background-color: var(--primary-color);
            padding: 1rem;
            box-shadow: var(--shadow);
        }

        .navbar-brand {
            font-size: 1.5rem;
            font-weight: bold;
        }

        .nav-link {
            font-weight: 500;
            padding: 0.5rem 1rem !important;
            transition: var(--transition);
        }

        .nav-link:hover {
            color: var(--accent-color) !important;
        }

        .hero-section {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--text-light);
            padding: 5rem 0;
            margin-bottom: 2rem;
        }

        .hero-section h1 {
            font-weight: 700;
            margin-bottom: 1.5rem;
        }

        .player-card, .feature-card {
            border-radius: 15px;
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: transform 0.3s ease;
            margin-bottom: 20px;
            background: white;
            height: 100%;
            border: none;
        }

        .player-card:hover, .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1);
        }

        .player-card .position-relative {
            width: 100%;
            padding-bottom: 100%;
            position: relative;
            overflow: hidden;
        }

        .player-card img,
        .player-card .card-img-top {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .hero-section .position-relative {
            padding-bottom: 0;
        }

        .hero-section img {
            position: relative;
            width: 100%;
            height: auto;
            max-height: 400px;
            object-fit: cover;
            border-radius: 15px;
        }

        .card-body {
            padding: 1.25rem;
        }

        .price-badge, .vip-badge {
            position: absolute;
            top: 1rem;
            right: 1rem;
            background: var(--accent-color);
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 25px;
            font-weight: 500;
        }

        .vip-badge {
            background: #f1c40f;
        }

        .rating {
            color: #f1c40f;
        }

        .btn {
            padding: 0.8rem 1.5rem;
            border-radius: 25px;
            font-weight: 500;
            transition: var(--transition);
        }

        .btn-primary {
            background-color: var(--accent-color);
            border-color: var(--accent-color);
        }

        .btn-primary:hover {
            background-color: #c0392b;
            border-color: #c0392b;
            transform: translateY(-2px);
        }

        .btn-outline-light:hover {
            background-color: var(--accent-color);
            border-color: var(--accent-color);
        }

        .modal-content {
            border-radius: 15px;
            border: none;
        }

        .modal-header {
            background-color: var(--primary-color);
            color: white;
            border-radius: 15px 15px 0 0;
            border-bottom: none;
            padding: 1.5rem;
        }

        .modal-body {
            padding: 1.5rem;
        }

        .modal-footer {
            border-top: none;
            padding: 1.5rem;
        }

        .form-control, .form-select {
            border-radius: 10px;
            padding: 0.8rem 1rem;
            border: 1px solid #ddd;
        }

        .form-control:focus, .form-select:focus {
            box-shadow: 0 0 0 0.2rem rgba(231, 76, 60, 0.25);
            border-color: var(--accent-color);
        }

        .animate-fade-in {
            animation: fadeIn 0.5s ease-in;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @media (max-width: 768px) {
            body {
                font-size: 16px;
                line-height: 1.5;
            }
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="fas fa-dice me-2"></i>
                مكان الكراج
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" href="index.html">الرئيسية</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="players.html">احجز لاعب</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about.html">عن المكان</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown">
                            الألعاب
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#tarneeb">طرنيب</a></li>
                            <li><a class="dropdown-item" href="#trex">تركس</a></li>
                            <li><a class="dropdown-item" href="#hand">هاند</a></li>
                        </ul>
                    </li>
                </ul>
                <div class="d-flex">
                    <a href="tel:+1234567890" class="btn btn-outline-light">
                        <i class="fas fa-phone me-2"></i>
                        اتصل بنا
                    </a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section with Garage Image -->
    <section class="hero-section text-center">
        <div class="container animate-fade-in">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <h1 class="display-4 mb-4">استمتع بأفضل جلسات الورق</h1>
                    <p class="lead mb-4">العب طرنيب وتركس مع أفضل اللاعبين في أجواء مريحة مع شاي طازج 🎴</p>
                    <a href="players.html" class="btn btn-primary btn-lg">
                        <i class="fas fa-user-friends me-2"></i>
                        احجز لاعبك المفضل
                    </a>
                </div>
                <div class="col-md-6 mt-4 mt-md-0">
                    <img src="images/garage.jpg" alt="مكان الكراج" class="img-fluid rounded shadow-lg">
                </div>
            </div>
        </div>
    </section>

    <!-- Video Section -->
    <section class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-5">شاهد أجواء الجلسات</h2>
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <div class="ratio ratio-16x9 rounded shadow-lg overflow-hidden">
                        <iframe src="فيديو الكراج.mp4" title="جلسات الكراج" allowfullscreen></iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- VIP Guests Section -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">ضيوف الشرف</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="player-card animate-fade-in">
                        <div class="position-relative">
                            <img src="عبود.jpg" class="card-img-top" alt="عبود زاك">
                        </div>
                        <div class="card-body text-center">
                            <h5 class="card-title">عبود زاك</h5>
                            <p class="card-text text-muted">مقلد السيارات</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="player-card animate-fade-in">
                        <div class="position-relative">
                            <img src="وليد شقفة.jpg" class="card-img-top" alt="وليد شقفة">
                        </div>
                        <div class="card-body text-center">
                            <h5 class="card-title">وليد شقفة</h5>
                            <p class="card-text text-muted">لاعب جيد</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="player-card animate-fade-in">
                        <div class="position-relative">
                            <img src="ايهم.jpg" class="card-img-top" alt="ايهم">
                        </div>
                        <div class="card-body text-center">
                            <h5 class="card-title">ايهم</h5>
                            <p class="card-text text-muted">مشاهد عصبي</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="player-card animate-fade-in">
                        <div class="position-relative">
                            <img src="ابو مازن.jpeg" class="card-img-top" alt="مانيلا">
                        </div>
                        <div class="card-body text-center">
                            <h5 class="card-title">مانيلا</h5>
                            <p class="card-text text-muted">لاعب مستفز</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="player-card animate-fade-in">
                        <div class="position-relative">
                            <img src="مازن.jpg" class="card-img-top" alt="مازن">
                        </div>
                        <div class="card-body text-center">
                            <h5 class="card-title">مازن</h5>
                            <p class="card-text text-muted">مشاهد عكيك</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="player-card animate-fade-in">
                        <div class="position-relative">
                            <img src="سلامة.jpg" class="card-img-top" alt="سلامة">
                        </div>
                        <div class="card-body text-center">
                            <h5 class="card-title">سلامة</h5>
                            <p class="card-text text-muted">محترف هاندس</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features -->
    <section class="py-5 bg-light">
        <div class="container">
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="feature-card text-center animate-fade-in">
                        <i class="fas fa-trophy fa-3x mb-4"></i>
                        <h3 class="h4 mb-3">لاعبين محترفين</h3>
                        <p class="text-muted">استمتع باللعب مع أفضل لاعبي الطرنيب والتركس في المنطقة</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="feature-card text-center animate-fade-in">
                        <i class="fas fa-mug-hot fa-3x mb-4"></i>
                        <h3 class="h4 mb-3">شاي طازج</h3>
                        <p class="text-muted">استمتع بأفضل أنواع الشاي الطازج خلال جلستك</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="feature-card text-center animate-fade-in">
                        <i class="fas fa-home fa-3x mb-4"></i>
                        <h3 class="h4 mb-3">أجواء مريحة</h3>
                        <p class="text-muted">مكان مريح ومجهز خصيصاً لجلسات الورق</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-5">
        <div class="container">
            <div class="contact-info text-center animate-fade-in">
                <h2 class="mb-4">تواصل معنا</h2>
                <div class="row justify-content-center">
                    <div class="col-md-6">
                        <div class="d-flex justify-content-center align-items-center mb-3">
                            <i class="fas fa-phone fa-2x me-3"></i>
                            <div class="text-start">
                                <h5 class="mb-1">قصي نزيه - مسؤول الكراج</h5>
                                <a href="tel:+1234567890" class="text-decoration-none">+1234567890</a>
                            </div>
                        </div>
                        <div class="d-flex justify-content-center align-items-center">
                            <i class="fas fa-clock fa-2x me-3"></i>
                            <div class="text-start">
                                <h5 class="mb-1">أوقات العمل</h5>
                                <p class="mb-0">يومياً من 4 مساءً حتى 12 صباحاً</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Modal for Image Preview -->
    <div class="modal fade" id="imageModal" tabindex="-1">
        <div class="modal-dialog modal-lg modal-dialog-centered">
            <div class="modal-content">
                <div class="modal-header border-0">
                    <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body text-center p-0">
                    <img src="" id="modalImage" class="img-fluid" alt="صورة كبيرة">
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="text-center">
        <div class="container">
            <p class="mb-0">جميع الحقوق محفوظة &copy; 2025 مكان الكراج</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // تحديد جميع الصور التي نريد أن تكون قابلة للنقر
            const images = document.querySelectorAll('.player-card img');
            const modalImage = document.getElementById('modalImage');
            
            images.forEach(img => {
                img.style.cursor = 'pointer';
                img.addEventListener('click', function() {
                    modalImage.src = this.src;
                    new bootstrap.Modal(document.getElementById('imageModal')).show();
                });
            });
        });
    </script>
</body>
</html>
