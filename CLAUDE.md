# 인스타그램 릴스 자동 홍보 프로젝트

사용자의 비즈니스를 홍보하는 인스타그램 릴스를 만들고 업로드하는 프로그램입니다.

## 규칙

- **영상(릴스)을 만들 때는 반드시 `.claude/skills/hve-video-director` 스킬을 사용한다.**
  (`/hve-video-director <영상 요청>` 또는 Skill 도구로 호출)
- 릴스는 세로 9:16 비율로 만든다. 단, 스킬 규칙상 비율 등 Creative Brief 항목은 사용자에게 확인받는다.
- 인스타그램 업로드는 공식 Instagram Graph API(Content Publishing)만 사용한다. 아이디/비밀번호 로그인 자동화는 쓰지 않는다.
