
#디바이스 젬에서 user데이터베이스 추가하는 법(뷰 커스텀,컨트롤러 커스텀 방법)



변경사항
--------

유저 db에서 name필드 추가
config/db/migrate/20160921141318_devise_create_users

라우트 변경(필수)
config/route.rb

가입 컨트롤러 수정(필수)
controllers/users/sessions_controller.rb

가입 뷰에 name칸 추가
views/devise/registrations/new.html.erb

회원 이름 확인
views/home.index.html.erb



참고 사이트
------------------------------------------------------------------------------

디바이스 젬 깃헙 사이트
https://github.com/plataformatec/devise

예전 버전 디바이스 젬 한글번역본
http://rorlab.org/rblogs/44

디바이스 위키
https://github.com/plataformatec/devise/wiki/How-Tos

!!
------------------------------------------------------------------------------

받은 후에 bundle install과 rake db:migrate는 필수입니다.

동국대 멋쟁이사자처럼 4기 화이팅!!

