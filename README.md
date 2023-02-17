<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            padding-left: 12%; /* cách trong */
            padding-right: 12%;
            background-color: aliceblue; /* màu nền */
        }
        header{
            background-color: rgb(139, 245, 209); 
        }
        header table{ 
            width: 100%; /* độ rộng */
            text-align: right; /* canh vị trí chữ */
        }
        header a{
            text-decoration: none; /* bỏ gạch chân */
            color: orangered; /* màu chữ */
            margin: 10px; /* cách ngoài */
            font-size: 20px; /* cỡ chữ */
        }
        section{
            background-color: white;
        }
        section table{
            width: 100%;
            text-align: center;
        }
        article{
            background-color: white;
            padding-top: 50px;
            padding-bottom: 50px;
        }
        article table{
            width: 100%;
            text-align: center;
        }
        article img{
            border-radius: 15px;
        }
        article b{
            background-color: orange;
            color: white;
            border-radius: 0px 15px 15px 0px; /* bo góc trái trên - trên phải - dưới phải - dưới trái */
            padding: 10px;
        }
        aside{
          background-color: white;
          padding: 20px;
          text-align: center;
        }
        nav{background-color: aquamarine;
          text-align: center;
          padding: 10px;

        }
        nav input{
          height: 30px;
          width: 200px;
        }

        nav button{
          height: 35px;
        }
        aside table{
          text-align: center ;
          width: 100%;
          margin-top: 20px;
        }
        aside img{
          border-radius: 700px;
      
          border-radius: 50%; /* bo góc*/
        }
        aside b{
          background-color: orange;
          color: white;
          padding: 10px ; /* cách vô trong*/
        }
        footer{
          background-color: rgb(21, 233, 176);
          text-align: center;
          padding: 30px;
        }
        
    </style>
</head>
<body>
    <header>
        <table>
            <tr>
                <td><img width="120px" src="logo.png"></td>
                <td>
                    <a href="">Trang chủ</a>
                    <a href="#sanpham">Sản phẩm</a>
                    <a href="#chungnhan">Chứng nhận</a>
                    <a href="#phanhoi">Phản hồi</a>
                    <a href="">Hotline : 0987654321</a>
                </td>
            </tr>
        </table>
        <img width="100%" src="banner.png">
    </header>
    <section id="sanpham">
        <table >
        <tr>
                <td><img width="200px" src="sonmoi1.jpeg"></td>
                <td><img width="200px" src="sonmoi2.webp"></td>
                <td><img width="200px" src="sonmoi3.webp"></td>
                <td><img width="200px" src="sonmoi4.jpeg"></td>
            </tr>
            <tr>
                <td><h3>Son màu hồng</h3></td>
                <td><h3>Son màu đỏ</h3></td>
                <td><h3>Son màu chì</h3></td>
                <td><h3>Son màu đen</h3></td>
            </tr>
            <tr>
                <td><button>Mua ngay</button></td>
                <td><button>Mua ngay</button></td>
                <td><button>Mua ngay</button></td>
                <td><button>Mua ngay</button></td>
            </tr>
        </table>
    </section>
    <article id="chungnhan">
        <b>CHỨNG NHẬN CHẤT LƯỢNG</b>
        <table>
<tr>
                <td><h3>ĐẠT DANH HIỆU TOP 100</h3></td>
                <td><img width="400px" src="giaithuong100.jpeg"></td>
            </tr>
            <tr>
                <td><img width="400px" src="thuonghieu10.png"></td>
                <td><H3>ĐẠT HUÂN CHƯƠNG LAO ĐỘNG</H3></td>
            </tr>
        </table>
    </article>
    <nav>
        <input type="text">
        <button>NHẬP EMAIL ĐỂ NHẬN MÃ KHUYẾN MÃI</button>
    </nav>
    <aside>
      <b>Phản Hồi Của Khách Hàng</b>
    <table>
      <tr>
        <td><img width="200px" src="tranthanh.jpeg"></td>
        <Td><img width="200px" src="thuytien.jpeg"></Td>
        <td><img width="200px" src="denvau.jpeg"></td>
      </tr>
      <tr>
        <td><i>Trấn Thành: Son đẹp quá, mua cho vợ sài </i></td>
        <Td><i>Thủy Tiên: Xài mới có 1000 thỏi à  </i></Td>
        <td><i>Đen Vâu: Đặt mấy thùng tặng fan xài chơi </i></td>
      </tr>
    </table>
  </aside>
    <footer>
      <b>CÔNG TY TNHH SON ĐẸP NHẤT THẾ GIỚI</b>
      <br>
      <br>
      <b>Địa chỉ: 1 Quang Trung, Tân Chánh Hiệp, Quận 12, TP Hồ CHí Minh</b>
      <br>
      <br>
      <b>SĐT: 080566792 - Email: sale@sondep.com</b>
    </footer>
</body>
</html>
