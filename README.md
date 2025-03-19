<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مكان الكراج - أفضل مكان للعب الورق</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700&display=swap" rel="stylesheet">
    <link href="css/style.css" rel="stylesheet">
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
