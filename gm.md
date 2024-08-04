req
install
git
github desktop

... text editor

git / distributed version control system, 파일을 추적하는 방식
git hub / git provider

git hub, git lab, git bucket...

area /
working directory(area)
staging area
repository area

branch /

fork시 기본적으로 upstream 브랜치가 생성됨
upstream 브랜치를 통해 베이스 저장소의 변경사항을 요청받을 수 있음
/ex
?작업중인 프로젝트가 뒤쳐져 있고 베이스 저장소가 작업이 많이 된 최신코드라 할 때,
upstream/master 브랜치로 병합
베이스 저장소에서 fork할 당시의 커밋에서부터 베이스 저장소의 최신 커밋까지를 master로 업데이트
upstream/master 브랜치를 fetch하여 최신 commit으로 업데이트 후,
이를 master 브랜치로 merge
