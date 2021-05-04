![idscann.com](https://logo.idscann.com/1/cover.png)

# [idscann.com](https://www.idscann.com/)
idscann.com


example
https://note.nkmk.me/en/python-pillow-qrcode/

    face = Image.open('data/src/lena.jpg').crop((175, 90, 235, 150))

    qr_big = qrcode.QRCode(
        error_correction=qrcode.constants.ERROR_CORRECT_H
    )
    qr_big.add_data('I am Lena')
    qr_big.make()
    img_qr_big = qr_big.make_image().convert('RGB')

    pos = ((img_qr_big.size[0] - face.size[0]) // 2, (img_qr_big.size[1] - face.size[1]) // 2)

    img_qr_big.paste(face, pos)
    img_qr_big.save('data/dst/qr_lena2.png')
