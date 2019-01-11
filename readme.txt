hello Git!

快速设置 - 如果你以前做过这种事情
要么	
HTTPS
SSH

https://github.com/shsxtzzl/git01.git
通过 创建新文件 或上 载现有文件开始。我们建议每个存储库都包含 README， LICENSE和.gitignore。

...或在命令行上创建一个新的存储库
echo“#git01”>> README.md 
git init 
git add README.md 
git commit -m“first commit” 
git remote add origin https://github.com/shsxtzzl/git01.git
 git push -u origin master
...或从命令行推送现有存储库
git remote add origin https://github.com/shsxtzzl/git01.git
 git push -u origin master
...或从另一个存储库导入代码
您可以使用Subversion，Mercurial或TFS项目中的代码初始化此存储库。