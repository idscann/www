![idscann.com](https://logo.idscann.com/1/cover.png)



# [idscann.com](https://www.idscann.com/)
idscann.com



idscann Accounts

idscann Accounts is the centralized accounts system for all of the idscann-operated services, it provides Single Sign-On (SSO) experience for our users.



https://sourcegraph.com/docs/sourcegraph-accounts

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


## IdP

What is an identity provider?

An identity provider (IdP) is a product or service that helps manage identity. An IdP often handles the actual login process. Single sign-on (SSO) providers fit into this category. IdPs can be part of an IAM framework, but typically they don't help with managing user access.


## IDaaS

What is Identity-as-a-Service?

In some cases, IDaaS and IdP are essentially interchangeable
Identity-as-a-Service (IDaaS) is a cloud service that verifies identity. 
It is a SaaS offering from a cloud vendor, a way of partially outsourcing identity management.

The IDaaS vendor offers additional capabilities on top of identity verification and management. 
Depending on the capabilities offered by the IDaaS vendor, IDaaS can be a part of an IAM framework, or it can be the whole IAM system.


## IAM
How does IDSCANN assist with IAM and the cloud?

Softreck IDSCANN Access is an IAM product that monitors user access to any domain, application, or path hosted on Softreck Cloud. 
It integrates with SSO providers and allows administrators to alter and customize user permissions. 
Softreck Cloud Infrastructure Access helps enforce security policies for both on-premises internal employees and remote workers. 
