# ririkamomobami
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Shop Banner Pro</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100">

  <!-- Header -->
  <header class="bg-white shadow-md">
    <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-indigo-600">Shop Banner Pro</h1>
      <nav class="space-x-4">
        <a href="index.html" class="text-gray-700 hover:text-indigo-600">Trang chủ</a>
        <a href="products.html" class="text-gray-700 hover:text-indigo-600">Sản phẩm</a>
        <a href="ctv.html" class="text-gray-700 hover:text-indigo-600">Cộng tác viên</a>
        <a href="dashboard.html" class="text-gray-700 hover:text-indigo-600">Nạp tiền</a>
        <a href="admin.html" class="text-red-500 font-semibold">Quản trị</a>
        <a href="login.html" class="px-3 py-1 bg-indigo-600 text-white rounded">Đăng nhập</a>
      </nav>
    </div>
  </header>

  <!-- Banner -->
  <section class="bg-indigo-600 text-white py-20 text-center">
    <h2 class="text-4xl font-bold mb-4">Tạo banner đẹp cho sản phẩm của bạn</h2>
    <p class="text-lg mb-6">Nhanh chóng – Chuyên nghiệp – Miễn phí</p>
    <a href="products.html" class="bg-white text-indigo-600 px-6 py-2 rounded shadow hover:bg-gray-200">Xem sản phẩm</a>
  </section>

  <!-- Danh sách sản phẩm mẫu -->
  <section class="max-w-7xl mx-auto py-10 px-4">
    <h3 class="text-2xl font-semibold mb-6">Sản phẩm nổi bật</h3>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
      <div class="bg-white p-4 rounded shadow">
        <img src="https://via.placeholder.com/300x200" alt="Product" class="rounded mb-2">
        <h4 class="text-lg font-semibold">Banner sản phẩm A</h4>
        <p class="text-sm text-gray-600">Giá: 10.000đ</p>
      </div>
      <div class="bg-white p-4 rounded shadow">
        <img src="https://via.placeholder.com/300x200" alt="Product" class="rounded mb-2">
        <h4 class="text-lg font-semibold">Banner sản phẩm B</h4>
        <p class="text-sm text-gray-600">Giá: 15.000đ</p>
      </div>
      <!-- Thêm sản phẩm khác nếu muốn -->
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-white text-center py-4 border-t mt-10">
    <p class="text-gray-600 text-sm">© 2025 Shop Banner Pro. All rights reserved.</p>
  </footer>

</body>
</html>
