# CheckCalorie

A mobile application built with React Native and Expo that helps users track and manage their calorie intake. The app uses Google's Generative AI to analyze food images and provide nutritional information.

## Features

- 📸 Image-based food recognition
- 🔍 Detailed nutritional information
- 📊 Calorie tracking
- 🎯 User-friendly interface
- 📱 Cross-platform support (iOS & Android)

## Tech Stack

- React Native
- Expo
- TypeScript
- Jotai (State Management)
- Google Generative AI
- Expo Router
- React Navigation

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Expo CLI
- iOS Simulator (for iOS development)
- Android Studio (for Android development)

## Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd CheckCalorie
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm start
# or
yarn start
```

## Available Scripts

- `npm start` - Start the Expo development server
- `npm run android` - Run the app on Android
- `npm run ios` - Run the app on iOS
- `npm run web` - Run the app on web
- `npm run test` - Run tests
- `npm run lint` - Run linter

## Project Structure

```
CheckCalorie/
├── app/                 # Main application code
│   ├── api/            # API related code
│   ├── _layout.tsx     # Root layout component
│   ├── index.tsx       # Home screen
│   └── result.tsx      # Results screen
├── atoms/              # Jotai atoms for state management
├── assets/             # Static assets (images, fonts, etc.)
├── .expo/              # Expo configuration
└── .vscode/            # VS Code settings
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

# CheckCalorie (Phiên bản Tiếng Việt)

Ứng dụng di động được xây dựng bằng React Native và Expo giúp người dùng theo dõi và quản lý lượng calo nạp vào cơ thể. Ứng dụng sử dụng Google Generative AI để phân tích hình ảnh thức ăn và cung cấp thông tin dinh dưỡng.

## Tính năng

- 📸 Nhận diện thức ăn qua hình ảnh
- 🔍 Thông tin dinh dưỡng chi tiết
- 📊 Theo dõi lượng calo
- 🎯 Giao diện thân thiện với người dùng
- 📱 Hỗ trợ đa nền tảng (iOS & Android)

## Công nghệ sử dụng

- React Native
- Expo
- TypeScript
- Jotai (Quản lý trạng thái)
- Google Generative AI
- Expo Router
- React Navigation

## Yêu cầu hệ thống

- Node.js (phiên bản 14 trở lên)
- npm hoặc yarn
- Expo CLI
- iOS Simulator (để phát triển iOS)
- Android Studio (để phát triển Android)

## Cài đặt

1. Clone repository:
```bash
git clone [your-repository-url]
cd CheckCalorie
```

2. Cài đặt các thư viện:
```bash
npm install
# hoặc
yarn install
```

3. Khởi động máy chủ phát triển:
```bash
npm start
# hoặc
yarn start
```

## Các lệnh có sẵn

- `npm start` - Khởi động máy chủ phát triển Expo
- `npm run android` - Chạy ứng dụng trên Android
- `npm run ios` - Chạy ứng dụng trên iOS
- `npm run web` - Chạy ứng dụng trên web
- `npm run test` - Chạy các bài kiểm tra
- `npm run lint` - Kiểm tra lỗi code

## Cấu trúc dự án

```
CheckCalorie/
├── app/                 # Mã nguồn chính của ứng dụng
│   ├── api/            # Mã nguồn liên quan đến API
│   ├── _layout.tsx     # Thành phần layout gốc
│   ├── index.tsx       # Màn hình chính
│   └── result.tsx      # Màn hình kết quả
├── atoms/              # Jotai atoms cho quản lý trạng thái
├── assets/             # Tài nguyên tĩnh (hình ảnh, font chữ, v.v.)
├── .expo/              # Cấu hình Expo
└── .vscode/            # Cài đặt VS Code
```

## Đóng góp

1. Fork repository
2. Tạo nhánh tính năng (`git checkout -b feature/TinhNangMoi`)
3. Commit các thay đổi (`git commit -m 'Thêm tính năng mới'`)
4. Đẩy lên nhánh (`git push origin feature/TinhNangMoi`)
5. Tạo Pull Request