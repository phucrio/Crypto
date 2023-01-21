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
