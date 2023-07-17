# rzd-skills
автомонтировнае
https://basis.gnulinux.pro/ru/latest/basis/59/59._%D0%90%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5_%D0%BC%D0%BE%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_-_Autofs.html

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
