---
title: 프로젝트
date: 2024-06-11

type: landing

sections:
  - block: project
    content:
      title: school
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - school
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: project
    content:
      title: national
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - national
          # - 대전광역시
          # - 한동대
          # - 부산광역시

      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: false
      show_social: false
      columns: 2
---