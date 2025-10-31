# Team Collaboration Practice Project

> A collaborative project for practicing Git workflow, issue tracking, and team development processes.

## Overview

This repository serves as a training ground for team collaboration using Git and GitHub. Each team member creates their own profile and contributes to the project following established guidelines.

**Project Start Date:** October 30, 2024

## Team Members

| Name | GitHub | Folder |
|------|--------|--------|
| 김신우 (Kim Sinwoo) | [@rlatlsdn98](https://github.com/rlatlsdn98) | `sinwookim/` |
| 윤성원 (Yoon Sungwon) | TBD | `yoonsungwon/` |
| 손창우 (Son Changwoo) | TBD | `sonchangwoo/` |
| 임원석 (Lim Wonseok) | TBD | `wonsuk/` |

## Project Structure

```
teamprojectPrac/
├── README.md
├── sinwookim/
│   └── sinwookimProfile.md
├── yoonsungwon/
├── sonchangwoo/
└── wonsuk/
```

## Development Guidelines

### Branch Naming Convention

```
username/(issue-number)-issue-name
```

**Example:** `sinwookim/10-add-profile`

### Commit Message Guidelines

- Write clear, concise commit messages in Korean or English
- Include the issue number when applicable
- Format: `#<issue-number> <brief description>`

**Example:** `#10 자기소개 파일 추가`

### Folder Naming Rules

- Use full name in lowercase
- No spaces or special characters
- Korean names should be romanized

**Example:** `sinwookim`, `yoonsungwon`

### Pull Request Guidelines

1. **Title:** Clear and descriptive
2. **Description:** Explain what changes were made and why
3. **Review:** At least one team member should review before merging
4. **Comments:** Describe modifications as accurately as possible

## Contributing

### Workflow

1. **Create an Issue** for your task
2. **Create a Branch** following the naming convention
3. **Make Changes** in your designated folder
4. **Commit** with clear messages
5. **Push** to your branch
6. **Create a Pull Request** with detailed description
7. **Request Review** from team members
8. **Merge** after approval

### Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd teamprojectPrac
   ```

2. Create your branch:
   ```bash
   git checkout -b username/issue-number-description
   ```

3. Make your changes in your folder

4. Commit and push:
   ```bash
   git add .
   git commit -m "#<issue-number> <description>"
   git push origin username/issue-number-description
   ```

5. Create a Pull Request on GitHub

## Learning Objectives

- Practice Git branching and merging strategies
- Understand issue tracking and project management
- Experience code review processes
- Develop collaboration and communication skills
- Learn professional development workflows

## License

This is an educational project for learning purposes.