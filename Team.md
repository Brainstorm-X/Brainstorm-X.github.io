---
layout: default
type: Team
permalink: /Team/
---

<style>
/* 团队成员网格布局 */
.team-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 40px;
  margin: 3em 0;
}

/* 成员卡片样式 */
.team-member {
  text-align: center;
}

/* 圆形头像 */
.team-avatar {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid #eee;
  margin-bottom: 1em;
}

/* 成员名字（蓝色） */
.member-name {
  color: #2c7fb8;
  font-size: 1.1em;
  font-weight: 500;
  margin-bottom: 0.3em;
}

/* 成员职位 */
.member-title {
  font-size: 0.95em;
  color: #333;
  line-height: 1.4;
}

/* 分组标题 */
.team-section {
  margin-top: 4em;
  margin-bottom: 1em;
  font-size: 1.8em;
  font-weight: 600;
}

/* 响应式适配：手机端自动调整列数 */
@media (max-width: 768px) {
  .team-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 480px) {
  .team-grid {
    grid-template-columns: 1fr;
  }
}
</style>

---
# Faculty Members

<div class="team-grid">
  <div class="team-member">
    <img src="/assets/images/team/dq.jpg" alt="Qingxiong Tan" class="team-avatar">
    <div class="member-name">Qingxiong Tan</div>
    <div class="member-title">Assistant Professor</div>
  </div>
</div>

# Ph.D. Students

<div class="team-grid">
  <div class="team-member">
    <img src="/assets/images/team/student1.jpg" alt="Student 1" class="team-avatar">
    <div class="member-name">Student Name 1</div>
    <div class="member-title">Ph.D. Candidate (2023)</div>
  </div>
</div>

# Master Students

<div class="team-grid">
  <div class="team-member">
    <img src="/assets/images/team/student1.jpg" alt="Student 1" class="team-avatar">
    <div class="member-name">Student Name 1</div>
    <div class="member-title">M.S. student (2022 Fall)</div>
  </div>
</div>

# Undergraduate Students

<div class="team-grid">
  <div class="team-member">
    <img src="/assets/images/team/student1.jpg" alt="Student 1" class="team-avatar">
    <div class="member-name">Student Name 1</div>
    <div class="member-title">Undergraduate (2022)</div>
  </div>
</div>

