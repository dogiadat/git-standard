### Framgia git standard
Tham khảo [Framgia Git Flow](https://github.com/framgia/coding-standards/blob/master/vn/git/flow.md), [standard-version](https://github.com/conventional-changelog/standard-version)

## Mục đích của tài liệu
- Quy chuẩn đặt tên đồng nhất của các dự án.
- Tạo file CHANGELOG.md từ các nguyên tắc đặt tên.

## Nguyên tắc đặt tên branch

**Tùy vào dự án sẽ có nhưng quy tắc đặt branch khác nhau**

*Đối với dự án quản lý issue trên github/ waffle qua label*

- Đối với tính năng mới: `feature/#issue_id-ten-nhanh (ví dụ: `feature/#2-create-readme-file`)
- Đối với bug: `fix/#issue_id-ten-nhanh` (ví dụ: `fix/#3-login-with-facebook`)

*Đối với dự án quản lý issue trên redmine:*

*Đối với dự án quản lý issue trên backlog, ....*

## Nguyên tắc đặt tên commit
Nguyên tắc đặt tên commit sẽ đóng vai trò quyết định nội dung trong file CHANGLOG.md sẽ được tạo ra

**Mỗi loại issue tương ứng sẽ đặt tên commit theo format tương ứng**

*Tính năng mới:*

- `feat: nội dung commit` (ví dụ: `feat: user management`)

*Tính năng mới có thêm scope:*

- `feat(scope): nội dung commit` (ví dụ: `feat(lang): added vietnamese language`)

*Bug:*

- `fix(scope): nội dung commit` (ví dụ: `fix(login): can not login with facebook`)

*Có tính năng hoặc sự thay đổi lớn nào đó:*

  ```
  feat(scope) nội dung commit
  BREAKING CHANGE: thông tin thay đổi
  ```

*Trường hợp khác*

- `docs: nội dung commit` (ví dụ: `docs: hot fix readme`)

## Pull request rules
- Cách đặt tên, mô tả phù hợp theo lừng công cụ quản lý ticket (github, backlog, redmine,...)
- Ví dụ

## Version (tag) rules
- Cách đặt tên, cách lên version
- Ví dụ

## Hướng dẫn sử dụng tools tạo changelog
