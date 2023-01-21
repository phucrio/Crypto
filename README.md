# Crypto
Bùi Minh Phúc AT17B

# Tet_is_ya_best
Ciphertext bài cho:
```
lyl, rwns dmsfm rn wkmrx myf iyrx pynljorw, jn luy ejvvynl lxrqjljsmrw pynljorw jm ojyl mrh.
lyl jn knkrwwi pxsh luy ymq sp trmkrxi ls yrxwi pyexkrxi. 
eypsxy lyl, ojylmrhyny cxycrxy hrmi lujmvn psx luy luxyy hrjm qrin. 
luyi gwyrm luyjx uskny rmq qygsxrly fjlu pwsfyxn nkgu rn dkhbkrl lxyy sx cyrgu ewsnnsh. 
r ukvy rhskml sp pssq fjww ey eskvul eypsxy lyl psx hrdjmv lxrqjljsmrw qjnuyn. ermu gukmv, ermu lyl, vjs gur, asj rmq hkl, …rmq grmqjyn rxy luy pssqn lurl hknl uroy sm lyl uswjqrin.
qkxjmv lyl, cyscwy ojnjl luyjx xywrljoyn’ ushyn rmq vjoy fjnuyn. 
usfyoyx, luy ojylmrhyny eywjyoy lurl luy pjxnl ojnjlsx r prhjwi xygyjoyn jm luy iyrx qylyxhjmyn luyjx psxlkmy psx luy ymljxy iyrx, cyscwy myoyx ymlyx rmi uskny sm luy pjxnl qri fjluskl eyjmv jmojlyq pjxnl. 
rmsluyx gknlsh jn vjojmv wkgdi hsmyi, fujgu jn ckl jmls r xyq ymoywscy rn r nihesw sp wkgd rmq fjnu psx r myf rvy. 
lxrqjljsmrwwi, ywqyxn fjww vjoy wkgdi hsmyi ls gujwqxym rmq luy swqynl cyscwy jm luy prhjwi. usfyoyx, msfrqrin, cyscwy grm vjoy jl ls rmismy jmgwkqjmv pxjymqn, crxymln, myjvuesxn,… 
eynjqyn, ojylmrhyny knkrwwi vs ls crvsqrn sx lyhcwyn ls cxri psx uyrwlu, fyrwlu, nkggynn,… 
ls ojylmrhyny, lyl jn luy urccjynl ljhy sp rww iyrx rxskmq, hyheyxn jm r prhjwi grm vrluyx lsvyluyx, fujgu jn r hyrmjmvpkw hynnrvyn sp wkmrx myf iyrx pynljorw. 
rww jm rww, lyl jn rww reskl ergd ls sxjvjmn, ey vssq ls sluyxn, ymtsi luy cxygjskn hshyml, rmq fjnu psx luy eynl ls gshy.
luy pwrv jn: dgng{lyl_lyl_lyl_lyl_qym_xsj__gukg_grg_erm_mrh_hsj_lurl_mujyk_nkg_dusy__wko_pxsh_wkwkkkkkkkkkkkk}
```
Dự đoán đây là một loại mật mã thay thế 
Copy vào trang `https://www.dcode.fr/monoalphabetic-substitution`

![Screenshot_20230121_124940](https://user-images.githubusercontent.com/83689890/213845709-898a5876-f748-4fbb-8788-240dad5eba31.png)

Được flag là `KCSC{TET_TET_TET_TET_DEN_ROI__CHUC_CAC_BAN_NAM_MOI_THAT_NHIEU_SUC_KHOE__LUV_FROM_LULUUUUUUUUUUUU}`

Format lại thành chữ thường `KCSC{tet_tet_tet_tet_den_roi__chuc_cac_ban_nam_moi_that_nhieu_suc_khoe__luv_from_luluuuuuuuuuuuu}`

# Chuyến tàu vô tận

Trong file message.txt bài cho là một chuỗi nhị phân:

```
01010011 00110001 01000010 01010100 01010110 01101011 00110101 01010110 01010011 01101011 01001010 01010011 01010101 00110000 01000110 01001111 01010001 00110000 01001110 01001101 01010001 01010101 01010110 01000010 01010010 01010101 01010110 01001000 01010011 00110000 01110100 01010000 01010110 01010101 00111001 01000110 01010100 00110000 01010110 01000010 01010110 01000110 01010010 01010101 01010100 00110001 01001110 01000110 01010101 00110001 01001010 01010000 01010111 01010110 01001010 01000111 01010100 01000110 01001110 01001010
```

Sau đó ,ta chuyển về B64 được:
`S1BTVk5VSkJSU0FOQ0NMQUVBRUVHS0tPVU9FT0VBVFRUT1NFU1JPWVJGTFNJ`

![Screenshot_20230121_010605](https://user-images.githubusercontent.com/83689890/213846242-7a323a81-c79b-4d7e-964c-928693ee7fad.png)



Tiếp tục chuyển về ASCII:`KPSVNUJBRSANCCLAEAEEGKKOUOEOEATTTOSESROYRFLSI`
![Screenshot_20230121_010526](https://user-images.githubusercontent.com/83689890/213846220-ffa08f2f-5170-4ca0-b63c-225dcb0fb854.png)

Vì theo đề bài có keyword chuyến tàu vô tận,nên mình đoán đây là loại mật mã đường tàu (Rail fence)

Dán đoạn mã vào trang `https://www.boxentriq.com/code-breaking/rail-fence-cipher`

![Screenshot_20230121_011206](https://user-images.githubusercontent.com/83689890/213846371-50648ab9-6f9d-4ceb-ac03-07d3725cd798.png)

Được kết quả là `KCSCPLEASESAVERENGOKUKYOJUROBEFORELASTSTATION`

Format lại thành flag : `KCSC{PLEASESAVERENGOKUKYOJUROBEFORELASTSTATION}`


# ezenc
Nội dung cipher là 1 đoạn mã HEX :
```
4e544d7a4d44526c4e5451314d544d7a4e7a51304e6a59794e6d51305a5463324e5745304e7a5a6a4e7a553159544d784d7a6b305954597a4d7a457a4f5451304e6a497a4d6a4d354e7a4d304f54557a4e4455324f4459324e54457a5a444e6b
```

Mình dùng CyberChef để giải challenge này:


![Screenshot_20230121_011638](https://user-images.githubusercontent.com/83689890/213846470-c0cf7796-27be-43ce-b442-7ae850ee8bfe.png)
Chuyển unhex đoạn mã được :`NTMzMDRlNTQ1MTMzNzQ0NjYyNmQ0ZTc2NWE0NzZjNzU1YTMxMzk0YTYzMzEzOTQ0NjIzMjM5NzM0OTUzNDU2ODY2NTEzZDNk`

Tiếp tục chuyển B64 về ASCII:



![Screenshot_20230121_011813](https://user-images.githubusercontent.com/83689890/213846558-24024c6f-f885-4fdb-af15-7561d945b942.png)

Kết quả tiếp tục được một đoạn mã Hex :`53304e5451337446626d4e765a476c755a31394a63313944623239734953456866513d3d`

Tiếp tục tương tự tìm được flag : `KCSC{Encoding_Is_Cool!!!}`





![Screenshot_20230121_011956](https://user-images.githubusercontent.com/83689890/213846604-cef1bcb1-a0d8-4f34-8d64-4d4816e40d40.png)


# Waiting xor you

Đoạn code bài cho:
```
def xor(a: bytes, b: bytes):
    return bytes([a[i % len(a)] ^ b[i % len(b)] for i in range(max(len(a), len(b)))])


flag = b"KCSC{???????????????????????????}"
key = b"??????"
print(xor(flag, key))
#b'>0\x0c,\x1a+:=\x100(5*,\x08*(2<=\x11!> E!\x006Q3VP"'
```

Đầu tiên ,mình xor chuỗi kí tự bài cho `b'>0\x0c,\x1a+:=\x100(5*,\x08*(2<=\x11!> E!\x006Q3VP"'`  với chuỗi `"KCSC{` để tìm key:
![Screenshot_20230121_012541](https://user-images.githubusercontent.com/83689890/213846817-e2bdb4d3-ba84-4d18-9003-597e29a6ca2b.png)

Kết quả được 5 kí tự đầu của key là us_oa ,mình đoán kí tự cuối là f key sẽ là `us_oaf`


![Screenshot_20230121_012822](https://user-images.githubusercontent.com/83689890/213846911-ad8f4ce3-837e-4c6c-be5b-610980cbf5ca.png)

Đúng như dự đoán ta tìm được flag là `KCSC{MONO_IS__WEITINNN_F0R_Y0U##}`

# Truy lùng tổ chức áo đen
Đoạn code bài cho:
```
# Two people using DHKE, but a or b is small 
p = 94222223051318251788373116079823589263589635857630651803373651523757275090527 
g = 2

a = ???? 
A = 31822216633104443305987801224128660665880110686370239075045238816060763002874
b = ????
B = ????
secret = A^b mod p

# someone find B inline

x1 = 173184786344890217883981201779895724483
x2 = 253233715256032720399137001948100003639
x3 = 248014991081832114029625969097077251431

c1 = 101180082674764329281306139226797850515 #c1 ≡ B mod x1 
c2 = 83356617645903402795422165107262525830  #c2 ≡ B mod x2
c3 = 198527236046629960640791853635411802548 #c3 ≡ B mod x3

# if you have secret, please XOR with message to get flag
message = b't\x9e5\xe5/\xb9f\x1d\xffpa\x8b\xb0K\xfc\xe01\xfe\xba\x02\xf0\xe1\x8f0\xa5-\xa6\x0b\x02\x91Do'

```


Đây là loại mã hóa Diffie–Hellman Key Exchange
Xem thêm:`https://cryptobook.nakov.com/key-exchange/diffie-hellman-key-exchange`

![Screenshot_20230121_013116](https://user-images.githubusercontent.com/83689890/213847056-0d0fadf1-e3e7-4d38-a320-54d56147568e.png)


Ở đây để tìm được flag đầu tiên ta phải tìm được `secret` muốn tìm được `secret` ta phải biết được cặp số `A`,`b` hoặc `B`,`a` 

Đầu tiên ta đi tìm B ,muốn tính B ta phải giải được hệ phương trình đồng dư 

```
c1 ≡ B mod x1 
c2 ≡ B mod x2
c3 ≡ B mod x3
```

Ở đây mình dùng Thuật toán Chinese Remainder `https://www.dcode.fr/chinese-remainder`
Sau khi nhập x1,x2,x3 và c1,c2,c3 ta tính được B = `60947517329365239986236525240654550233850393868256513241317727505179049380957`


![Screenshot_20230121_015139](https://user-images.githubusercontent.com/83689890/213847696-0fecc30b-7eff-4000-a9d5-e0bae37592d3.png)


Bây giờ đã có `A` và `B` ta chỉ cần tìm được `a` hoặc `b` là sẽ tính được `secret` 

Vì đoạn code có note `Two people using DHKE, but a or b is small ` nên a hoặc b sẽ là số nhỏ dễ dàng tìm được

Mình cho chạy 1 đoạn code để thử tìm a và b 
```
for i in range(2,100000):
    if pow(g,i,p) == A:
        print("b = "+str(i))
        break;
    if pow(g,i,p) == B:
        print("a = "+str(i))
        break

```

![Screenshot_20230121_020011](https://user-images.githubusercontent.com/83689890/213848019-24314fa5-b813-4a3b-b0bf-74a0b450a408.png)


 Kết quả tìm được a = `51803`
 
 Theo công thức bài cho ta tính được `secret` = `28886891124482956689744265441861311809844009449147016760780113274230250890514`
 
 ![Screenshot_20230121_020145](https://user-images.githubusercontent.com/83689890/213848056-ceaadf11-74c4-4633-a2d5-3542933d7c3f.png)

Cuối cùng ta chuyển `secret` sáng bytes và xor với chuỗi kí tự bài cho ban đầu `b't\x9e5\xe5/\xb9f\x1d\xffpa\x8b\xb0K\xfc\xe01\xfe\xba\x02\xf0\xe1\x8f0\xa5-\xa6\x0b\x02\x91Do'`

![Screenshot_20230121_020250](https://user-images.githubusercontent.com/83689890/213848097-bebc7c65-9e6c-40df-b79a-1c47660a9522.png)

Tìm được flag là `KCSC{S3cr3t_m4k3_a_W0m3n_women!}`
