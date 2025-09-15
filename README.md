# Dự án Shopee Clone Typescript

## Chức năng chính

- Đăng ký, đăng nhập, đăng xuất (JWT)
- Danh sách sản phẩm: phân trang, tìm kiếm, lọc, sắp xếp
- Chi tiết sản phẩm: slider ảnh, mô tả rich text, mua hàng
- Giỏ hàng: thêm/sửa/xóa sản phẩm, đặt hàng
- Quản lý hồ sơ khách hàng: cập nhật thông tin, đổi mật khẩu, xem đơn hàng

## Công nghệ sử dụng

- UI/CSS: Tailwindcss, HeadlessUI
- State: React Query, React Context
- Form: React Hook Form
- Router: React Router
- Build tool: Vite
- API: RESTful API
- Đa ngôn ngữ: react.i18next
- SEO: React Helmet
- Unit Test, Storybook, ...

## Yêu cầu hệ thống

- **Node.js** >= 16.x.x ([Tải Node.js](https://nodejs.org/))
- **Yarn** (khuyến nghị) hoặc **npm**
  - Kiểm tra Yarn: `yarn -v`
  - Nếu chưa có Yarn: `npm install -g yarn` hoặc xem hướng dẫn [tại đây](https://classic.yarnpkg.com/en/docs/getting-started)

## Hướng dẫn cài đặt & chạy dự án

### 1. Clone dự án về máy

```bash
git clone <link-repo-của-bạn>
cd Shopee-Clone-Reactjs-master/Shopee
```

### 2. Cài đặt thư viện phụ thuộc

**Dùng Yarn:**
```bash
yarn install
```
**Hoặc dùng npm:**
```bash
npm install
```

### 3. Cài đặt các công cụ phát triển (nếu cần)

Nếu bạn setup mới, chạy lệnh sau để cài các công cụ lint, format:
```bash
yarn add eslint prettier @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-prettier prettier-plugin-tailwindcss eslint-plugin-react-hooks -D
```

Nếu dùng TailwindCSS, cài thêm:
```bash
yarn add -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

### 4. Chạy dự án

```bash
yarn dev
```
Hoặc với npm:
```bash
npm run dev
```



## Một số lệnh hữu ích

- **Kiểm tra lỗi code:**  
  `yarn lint`
- **Tự động sửa lỗi lint:**  
  `yarn lint:fix`
- **Kiểm tra format code:**  
  `yarn prettier`
- **Tự động format code:**  
  `yarn prettier:fix`

---

## Lưu ý

- Đảm bảo đã cài đúng phiên bản Node.js và Yarn.
- Nếu gặp lỗi thiếu package, hãy chạy lại `yarn install` hoặc `npm install`.


---

Chúc bạn cài đặt thành công!
