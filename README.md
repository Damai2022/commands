:octocat: ## Git commands :octocat:

git командуудын тайлбар,тусламжийн репо [эндээс үзнэ үү](www.apteka.mn)

git эхнээс нь дуустал гэдэг репо юм.

Командуудын жагсаалт ✨

git add *   **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

git add .   **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

git add -А  **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

git add [file1.txt] [file2.txt] [*.js] **file1.txt, file2.txt болон бүх javascript файлуудыг стэйжилнэ**

git branch **Бүх бранчуудыг жагсаалтаар харах**

git branch -a **Бүх бранчуудыг үзүүлнэ**

git branch --merge **merge хийгдсэн бранчуудын нэрийг үзүүлнэ**

git branch --no-merge **merge хийгдээгүй бранчуудын нэрийг үзүүлнэ**

git branch -r **Remote бранчуудыг үзүүлнэ**

git branch -vv **Tracking бранчуудыг үзүүлнэ**

git cherry-pick [hash_code] **hash_code кодтой коммитыг одоо байгаа бранч руу шууд оруулж ирнэ v79|02:34**

git commit [--amend] **Сүүлийн коммитыг засварлах, сайжруулах v61|02:30**

git config user.name [name] Өөрийн нэрийг энд тохируулна (github username байж болно)

git config user.email [email_address] Өөрийн имэйлийг энд тохируулна (github username ээ тавьж github руу push хийнэ)

git log --oneline Идэвхитэй, зөв засагдсан коммитуудын түүхийг харуулна. v60|09:47

git log --oneline --all --graph [hash_code] git түүхийг коммит бүрийг нэг мөрт багтааж бранчийн график зураастай хамт үзүүлнэ

git merge --squash [branch_name] branch_name бранчийг одоо байгаа бранч руу merge хийж оруулж ирэхдээ branch_name бранчийн бүх коммитийг нэгтгэн нэг коммит болгож оруулж ирнэ. Хэт бага үйлдэлтэй коммитуудыг нэгтгэн нэг болгоход хэрэглэнэ v75

git reflog Коммитуудын түүхийг жагсаалтаар харах. Репо дээр хийгдсэн өөрчлөлтийн түүхүүд v58|03:11

git reflog --all Коммитуудын түүхийг дэлгэрэнгүй жагсаалтаар харах v58|09:59

git rebase [branch_name] branch_name бранч дээр тулгуурлан одоо байгаа бранчийг дахин байрлуулж branch_name бранчын бүх кодыг одоо байгаа бранч руу оруулж ирнэ, түүхийг өөрчилж бичдэг боловч түүхийг шулуун болгож өгнө v76

git rebase -i [branch_name] ** Interactive rebasing: (Хөгжүүлэгч коммит бүр дээр яахыг өөрөө сонгож rebase хийнэ) ** v81

git remote add [remote_name] [remote_url] **remote_name нэртэй, remote_url хаягтай remote-ийг шинээр үүсгэнэ **

git remote prune [remote_name] Локал дээрх remote_name remote-ийг цэвэрлэнэ v45|07:36

git reset --hard [hash_code] Тухайн hash_code-той коммитруу шилжих, түүнээс хойшхи коммитууд хүчингүй болно v58|05:06

git reset --hard [HEAD@{number_commit}] Тухайн HEAD-ын дугаарыг ашиглан коммитруу шилжих, түүнээс хойшхи коммитууд хүчингүй болно v58|05:45

git revert [hash_code] hash_code кодтой коммит дээр хийгдсэн үйлдлүүдийг бүгдийг нь undo хийх шинэ коммит үүсгэнэ

git show [hash_code] Тухайн коммитын дэлгэрэнгүй мэдээллийг харуулна v58|03:46

git tag Бүх тагуудыг жагсааж үзүүлнэ

git tag -l "v0*" v0 оор эхэлсэн бүх тагуудыг шүүж үзүүлнэ
