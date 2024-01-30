Reference link 
https://www.youtube.com/watch?v=CkVrmLLHmuI&ab_channel=FajarStd

Create dashboard

Git command:
Nếu thư mục dự án chưa là một Git repository, hãy khởi tạo nó bằng lệnh:
 git init
Sử dụng các lệnh sau để thêm tất cả các tệp và commit chúng:
 git add .
 git commit -m "Initial commit"
Sử dụng lệnh git remote add để liên kết local repository của bạn với GitHub repository. Thay đổi YOUR_GITHUB_REPO_URL thành URL của GitHub repository của bạn:
  git remote add origin https://github.com/DiepKhac2289/Dashboard.git

Nếu có thay đổi gì thì dùng lệnh sau để code lên:
  git push -u origin master (git push thôi cũng được)

Pull về nếu branch name là master thì dùng lệnh:
  git pull origin master

