---
layout: post
category: blog
title:  "블로그 생성 완"
date:   2024-04-20 22:19:00 +0900
#nextPart: _posts/2021-01-30-example.md #Next part.
#prevPart: _posts/2021-01-30-example.md #Previous part.
#og_image: assets/example.png #Open Graph preview image.
#og_description: "Example description." #Open Graph description.
---

오랜만에 다시 블로그 생성 완..!


테마를 뭘 할까 하다가 슥 보고 맘에 든 [simplex](https://github.com/andreondra/jekyll-theme-simplex)라는 테마를 잡았는데
이걸 내 맘에들게 바꾸려고 낑낑대다가 하루가.. 지나가... 버렸다......

jekyll 테마 변경은 처음 해봤는데 아무리 수정을 해도 `bundle exec jekyll serve`를 실행시키는 순간 바꾼게 날아가버려서 왜이러세요?!!!! 하다가 서치하면서 그냥 막 바꾼다고 적용되는게 아니고 테마와 페이지가 생성되는 구조를 알아야 바꿀 수 있는걸 알게 되었음

암튼 그래서 About 페이지 만들고 이것저것 줄간격 열심히 고쳐서 지금의 형태로 만들었다

아이콘은 아직 맘에드는게 없어서 보류

어차피 심플한걸 좋아하기도 하고 지금 당장은 Archives나 Tags 이런 기능이 필요없을 것 같아서 그대로 갈 것 같은데 나중에 혹시라도 필요하게되면 대 보수공사를 하거나 테마를 갈아타야 할 것 같다


다른 심플 테마들
- [Lanyon](https://jekyllthemes.io/theme/lanyon)
- [YAT](https://github.com/jeffreytse/jekyll-theme-yat)
- [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)



라고 쓰고 github에 push를 했는데 또 자꾸 에러가 나는 것임 부들부들   
   

이 테마를 github에서는 불러오지를 못해서 결국 또 오만 삽질 끝에 알아낸건

github에서 돌아가게 하려면   
- `remote_theme: andreondra/jekyll-theme-simplex` 로 써줘야 하고
- `theme: jekyll-theme-simplex` 이건 주석처리 해야함

근데!! 또 저렇게 하면 로컬에서 `bundle exec jekyll serve`이 안돌아가는 것임!! 답답해 죽는줄   


결론: 
- 로컬에서 확인하고 싶으면 `theme: jekyll-theme-simplex`을 살려야 함
- github에서 돌아가게 하려면 `theme: jekyll-theme-simplex` 주석 처리
   


업로드 하고보니 메인 페이지에 제목 아래 내용이 아주 구구절절 너무 많이 보이는 이슈가 있다   
이건 내일 보수공사를 하도록 하겠어요


