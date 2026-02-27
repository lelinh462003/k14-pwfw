# Giới thiệu

Project test cho website blog của khóa học

- Môi trường dev: https://pw-practice-dev.playwrightvn.com
- Môi trường production: https://pw-practice.playwright.com

# Cấu trúc thư mục

```
├── node_modules
├── package-lock.json
├── package.json
├── playwright.config.ts
├── pom
│   ├── dashbaord
│   └── storefront
├── README.md
├── tests
│   ├── dashbaord
│   ├── example.spec.ts
│   └── storefront
└── utils
    └── .gitkeep
```

- Cấu trúc dự án tổ chức theo module, mỗi module nằm trong một thư mục riêng biệt.
- Các file test tổ chức theo từng action.

#Convention

## Quy tắc đặt tên

- camelCase: cho tên biến, tên hàm, tên method.
- kebad-case: cho tên file, tên thư mục
  -....

##Coding convention

- Luôn sử dụng cặp ngoặc nhọn dù chỉ có 1 if...

Bad:

```javascript
if (condition) a = 10;
```

Good:

```javascript
if (condition) {
    a = 10;
}
```

## Quy tắc tạo PR

- tên branch:
- title PR: luôn luôn có ticket ID
- body: mô tả ngắn ngọn thay đổi

## Quy tắc thêm mới thư viện

- luôn test các case trước khi thêm
- cân nhắc xem có thực sự cần không?

## Một số mục tham khảo

- [Làm thế nào để viết test](documentaions/how-to.md)
