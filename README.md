# Website Sư Đoàn 316 "Bông Lau"

Trang web tưởng niệm lịch sử anh hùng của Sư đoàn 316, được xây dựng bằng HTML, CSS và JavaScript thuần.

## 📁 Cấu Trúc Dự Án

```
project/
├── index.html              # Trang chính
├── README.md               # Hướng dẫn dự án
├──
├── css/                    # Thư mục CSS
│   ├── reset.css          # Reset styles và biến CSS
│   ├── navigation.css     # Styles cho navigation
│   ├── components.css     # Components và buttons
│   ├── hero.css          # Hero section
│   ├── history.css       # History section
│   ├── timeline.css      # Timeline section
│   ├── battles.css       # Battles section
│   ├── gallery.css       # Gallery section
│   ├── memorial.css      # Memorial section
│   ├── footer.css        # Footer section
│   └── responsive.css    # Media queries và responsive
│
└── js/                    # Thư mục JavaScript
    ├── language.js        # Quản lý ngôn ngữ
    ├── navigation.js      # Navigation và scroll
    ├── modal.js          # Modal gallery
    ├── animations.js     # Animations và effects
    ├── events.js         # Event handlers
    └── main.js           # Khởi tạo ứng dụng
```

## 🎨 Tính Năng

### ✅ Giao Diện

- **Responsive Design**: Hoạt động tốt trên mọi thiết bị
- **Navigation**: Menu cố định với smooth scrolling
- **Hero Section**: Banner chính với thông tin sư đoàn
- **Interactive Timeline**: Dòng thời gian lịch sử tương tác
- **Battles Section**: Các trận đánh qua từng thời kỳ
- **Gallery**: Thư viện ảnh với modal xem phóng to
- **Memorial**: Phần tưởng niệm anh hùng liệt sĩ

### ✅ Chức Năng

- **Đa ngôn ngữ**: Hỗ trợ Việt/Anh với lưu trữ localStorage
- **Mobile Menu**: Hamburger menu cho mobile
- **Smooth Scrolling**: Cuộn mượt mà giữa các sections
- **Image Modal**: Xem ảnh phóng to với keyboard support
- **Print Support**: Tối ưu cho in ấn
- **Accessibility**: Hỗ trợ navigation bằng keyboard

## 🛠️ Cấu Trúc CSS

### Reset & Variables (`css/reset.css`)

- CSS Reset
- CSS Custom Properties (màu sắc, shadows, transitions)
- Base styles cho body và container

### Navigation (`css/navigation.css`)

- Fixed navigation bar
- Mobile hamburger menu
- Active link highlighting
- Scroll effects

### Components (`css/components.css`)

- Buttons (primary, secondary, battle-specific)
- Section headers
- Badges và labels
- Modal styling
- Animations

### Sections

- `hero.css` - Hero section với background và overlay
- `history.css` - Overview section với stats grid
- `timeline.css` - Interactive timeline với dots và images
- `battles.css` - Battle cards grid
- `gallery.css` - Image gallery với hover effects
- `memorial.css` - Memorial section với dark theme
- `footer.css` - Footer với links và social media

### Responsive (`css/responsive.css`)

- Media queries cho mobile/tablet
- Print styles
- Accessibility enhancements
- Loading states

## 🔧 Cấu Trúc JavaScript

### Language Management (`js/language.js`)

- Translations object cho Việt/Anh
- Language switching functions
- LocalStorage persistence
- Navigation items translation

### Navigation (`js/navigation.js`)

- Scroll-based active navigation
- Mobile menu toggle
- Smooth scrolling between sections
- Navbar background effects

### Modal (`js/modal.js`)

- Gallery modal functionality
- Keyboard support (ESC to close)
- Click outside to close
- Image loading and display

### Animations (`js/animations.js`)

- Intersection Observer cho scroll animations
- Image preloading
- Loading state management
- Error handling cho images

### Events (`js/events.js`)

- Battle details handlers
- Memorial message handler
- Button click events
- Accessibility enhancements
- Print preparation

### Main (`js/main.js`)

- Application initialization
- DOM ready event handler
- Global function exports
- Performance optimizations

## 🎯 Màu Sắc Chủ Đạo

```css
--vn-red: #da2128          /* Đỏ quốc kỳ */
--vn-yellow: #ffdd00       /* Vàng ngôi sao */
--military-navy: #2c3e50   /* Xanh navy quân đội */
--bronze: #cd7f32          /* Đồng */
--honors-green: #2e8b57    /* Xanh vinh danh */
```

## 📱 Responsive Breakpoints

- **Desktop**: > 1200px
- **Tablet**: 768px - 1199px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

## 🚀 Hướng Dẫn Sử Dụng

1. **Chạy Website**: Mở `index.html` trong trình duyệt
2. **Chỉnh Sửa Nội Dung**: Sửa file `index.html`
3. **Thay Đổi Styles**: Sửa các file trong thư mục `css/`
4. **Thêm Chức Năng**: Sửa các file trong thư mục `js/`
5. **Thêm Ngôn Ngữ**: Cập nhật object `translations` trong `js/language.js`

## 🎨 Customization

### Thay Đổi Màu Sắc

Sửa CSS variables trong `css/reset.css`:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
}
```

### Thêm Section Mới

1. Thêm HTML trong `index.html`
2. Tạo CSS file mới trong `css/`
3. Import CSS file vào `index.html`
4. Thêm navigation link nếu cần

### Thêm Tính Năng JS

1. Tạo function trong file JS phù hợp
2. Gọi function trong `js/main.js`
3. Thêm event listeners nếu cần

## 📄 Browser Support

- **Modern Browsers**: Chrome, Firefox, Safari, Edge
- **Mobile Browsers**: iOS Safari, Chrome Mobile
- **Features Used**: CSS Grid, Flexbox, Intersection Observer
- **Fallbacks**: Graceful degradation cho older browsers

## 📝 Ghi Chú

- Website được thiết kế tôn trọng lịch sử quân sự Việt Nam
- Sử dụng ảnh stock do không có ảnh thật từ thời kỳ lịch sử
- Nội dung dựa trên nghiên cứu lịch sử có sẵn
- Code được tối ưu cho hiệu năng và SEO
