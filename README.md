# LED MATRIX,CARD, CONTROLLER: https://www.hdwell.com/Download/index.html


## P2__160px x 80px
-**P2** : IC_(FM6363 -5958)---FW v23_08_03_30(R712)---_SW(HDPLAYER,HDSET)_

-**P2** : IC_(DP3264S -5958)---FW v25_10_65_30(R712)---_SW(HDPLAYER,HDSET)_


## P2.5__128px x 64px
-**P2.5** : IC_(1065L -138)---FW v25_10_65_30(R712)---_SW(HDPLAYER,HDSET)_


## P3__64px x 64px
-**P3** : IC_(6124 -138)---FW v23_08_03_30(R712)---_SW(HDPLAYER,HDSET)_

-**P3** : IC_(DP3264 -7258)------FW v23_08_03_30(R712)---_SW(HDPLAYER,HDSET)_

## P3.076 __104px x 52px
-**P3.091** : IC_(16169SH -2012)---FW v25_10_65_30(R712)---_SW(HDPLAYER,HDSET)_



## P4__80px x 40px 
-**P4** : IC_(ICN2037 -7258)---C08L---_SW(HDPLAYER,HDSET)_



-**P4** : IC_(DP3264SF -7258)------FW v25_10_65_30(R712)---_SW(HDPLAYER,HDSET)_



## P5__64px x 32px
-**P5 - 1/8S** : IC_(ICN2037)---C85---_SW(HD2018, HD2020)_

-**P5 - 1/8S** : IC_(3265S_7258)---FW v9.8.7.71(C08L)---_SW(HDPLAYER,HDSET)_

-**P5 - 1/10S** : IC_(FM6373-7258)---FW v25_16_65_30(R712---_SW(HDPLAYER,HDSET)_


## P10__32px x 16px
-**P10 SEMI NEW - 1/8S** : IC_(MB5125) ---_SW(HD2018, HD2020)_

-**P10 SEMI- 1/8S** : default name ---_SW(HD2018, HD2020)_

-**P10 ĐỎ** : C6  ---_SW(HD2018, HD2020)_

-**P10 FULL 1/4S** : C20 ---_SW(HD2018, HD2020)_


#




# LED DÂY FULL

## D20 FULL 
- **Cực màu**: GBR -- IC(8206,8208,1903)---FULL MINI,K8AC, H8

## D30 
- **Cực màu**: GBR -- IC(8206,8208,1903)

## D50 
- **Cực màu**: GRB -- IC(8206,8208,1903)-- OZO(8K)

## * Chú ý led dây full
  + Chiều led chạy
  + Cực màu led
  + Khi led lỗi hoặc chết bóng nên kiểm tra xem còn nhận tín hiệu không , nếu không thi thay từ 2-3 bóng trở lên (trước và sau bóng lỗi) là an toàn nhất.

# LED DẢI FULL 

## IC_16703
- **Cực màu**: RBG -- IC(8206,8208,1903)-- OZO(8K)
  
## IC_WS2813
- **Cực màu**: GRB -- FULLMINI
  
# MẠCH ĐIỀU KHIỂN FULL OZO : 4 CỔNG , 8 CỔNG 
- Đều xuất file thẻ nhớ -> Format ổ đĩa của mạch -> Sau đó copy file đã xuất vào trong ổ đia vừa format.
- Khi đồng bộ nhiều mạch như sau:
    - Ví dụ cần dùng 14 cổng
      + Chọn 2 mạch 8 cổng ozo
      + Chương trình gồm 16 cổng ( 14 cổng chính và 2 cổng ảo )
      + Mạch 1 từ cổng 1 đến 7 + 1 cổng ảo(1 điểm led bất kì) , mạch 2 từ cổng 1 đến 7 + 1 cổng ảo(1 điểm led bất kì).
      + Khi xuất chương trình để nạp cho 2 mạch -> xuất dạng file thẻ nhớ.
      + Mạch 1 xuất từ cổng 1 sau đó lưu lại rồi bắt đầu xuất. Mạch 2 bắt đầu từ cổng 9, lưu lại rồi xuất.

# Bộ đk H2-AC
- 2 nút ngoài cùng tay trái: tăng giảm tốc độ tương ứng với LED 7 segment ngoài cùng tay phải
- 2 nút bên cạnh từ trái sang: chọn chương trình ứng với LED 7 segment ngoài cùng tay phải vào 1 LED
- nút Test : chọn CH-3 để test các loại led full thông thường.
- nut Menu : Các chức năng như (IC, cực màu, tốc độ).
  

# PHẦN MỀM SUPERLED

## SUPERLED với H2-AC và D30F tự nháy
- Cực màu D30F tự nháy trong Superled là : BGR
- Chọn IC khi xuất file và trên bộ H2 đều là 1903.
- Dùng 1 dây data(green) nói vào chân data bộ điều khiển


## SUPERLED với H2-AC và F8_9883 không tự nháy
- Cực màu F8_9883 trong Superled là : RGB
- Chọn IC khi xuất file và trên bộ H2 đều là 9883 hoặc 1903
- Chặp dây green và blue lại rồi nối vào chân data bộ H2.
















