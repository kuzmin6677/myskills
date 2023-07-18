# rzd-skills
автомонтировнае
https://basis.gnulinux.pro/ru/latest/basis/59/59._%D0%90%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5_%D0%BC%D0%BE%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_-_Autofs.html

##CHAT GPT
https://gpt-chatbot.ru/
##mail
https://cloud.mail.ru/public/8rnF/gTdApTkrV

###
Всем права sudo
ipa sudorule-add ANY \
    --hostcat=all \
    --cmdcat=all \
    --runasusercat=all \
    --runasgroupcat=all

ipa sudorule-add-user ANY \
    --users=user --groups=group

ipa sudorule-add-option ANY \
    --sudooption='!authenticate'

systemctl restart ipa

#DDNS
https://linux-admins.ru/article.php?id_article=77&article_title=%D0%9D%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0%20%D0%B4%D0%B8%D0%BD%D0%B0%D0%BC%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B3%D0%BE%20%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B7%D0%BE%D0%BD%D1%8B%20%D0%BD%D0%B0%20DNS-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%B5%20Bind

https://serveradmin.ru/ustanovka-i-nastroyka-iredmail/
https://www.dmosk.ru/instruktions.php?object=iredmail-ubuntu#graylisting

#ssl for free ipa
https://itdraft.ru/2023/03/20/resheno-freeipa-pki-sozdaem-i-podpisyvaem-ssl-sertifikat/
