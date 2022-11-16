# 1.commit模板

所有commit必须使用以下格式:
```plaintext
<type>(<scope>): <subject>
```
其中\<scope\>是可选的，冒号必须是英文冒号，后面追加一个空格。\<type\>只允许使用以下标识：

* 🧩feat: 新功能;
* 🐛fix/to
  * 适合于一次提交直接修复问题;
  * 适合于多次提交,最终修复问题提交时使用fix;
* 📄doc: 更新了文档;
* 📐style: 修改了代码格式;
* 🏗️refactor: 重构;
* 🪄perf: 优化;
* 🧪test: 增加测试;
* 👟chore: 构建过程或辅助工具的变动;
* ⏮️revert: 回滚到上一个版本;
* 🪡merge: 代码合并;
* 🪐sync: 同步