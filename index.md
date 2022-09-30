#master 1

git init // local repo oluşturuyo

git status // branch hakkında bilgi veriyo

git add . // brnachde değişikleri kaydediyo

git commit -m // mesajla birlikte commitliyo

git log // logları getiriyo

git commit --amend // yeni commit etmeden varolan committe düzenleme yapmak \* bu komutla eklenmiştir

git commit --amend -m "" // commit mesajı değiştirmek için varolan birşey

git revert 64d36cb9b604b2552a11148461df94b422147da5 // yapılan commiti geri alma commit hash ile

git reset --hard 64d36cb9b604b2552a11148461df94b422147da5 // commit head i taşıyor

git diff hasha..hashb filename // diff patch teki difff in aynısı

git branch // branchleri gösteriri

git branch name // name isimli branch oluşturur

git checkout name // name isimli branche geçer

git checkout -b name // name oluşturur ve geçiş yapar

git branch -D name // name branch siler

git merge branchname // merge

