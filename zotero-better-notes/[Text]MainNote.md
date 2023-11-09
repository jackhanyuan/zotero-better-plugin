# [Text] MainNote 适配Zotero 6 7 主笔记模板 简约清晰风格

三级大纲，根据需求，可自行修改各级标题

关于此模版的一些常见问题，可以参考[discussions/772](https://github.com/windingwind/zotero-better-notes/discussions/772)

## Zotero MainNote Template

```yaml
# Zotero MainNote Template
# @author [jackhanyuan](https://github.com/jackhanyuan)
# @source [zotero-better-plugin](https://github.com/jackhanyuan/zotero-better-plugin)
# This template is specifically for importing/sharing, using better 
# notes 'import from clipboard': copy the content and
# goto Zotero menu bar, click Edit->New Template from Clipboard.  
# Do not copy-paste this to better notes template editor directly.
name: "[Text]MainNote"
content: |-
  <span>
    <h1 style="color:#5686bf; background-color:#eef9fd;">MainNote Title✍</h1>
  </span>
  
  <table>
    <tr>
      <td style="color:#193c47; background-color:#dbeedd; padding:8px;">
        <b>👨‍🎓 Author：</b>
      </td>
    </tr>
    <tr>
      <td style="color:#193c47; background-color:#f3faf4; padding:8px;">
        <b>🌟 Remarks：</b>
      </td>
    </tr>
    <tr>
      <td style="color:#193c47; background-color:#dbeedd; padding:8px;">
        <b>🎯 Tags：</b>
      </td>
    </tr>
    <tr>
      <td style="color:#193c47; background-color:#f3faf4; padding:8px;">
        <b>📅 Note Date：</b>${new Date().toLocaleString()}
      </td>
    </tr>
  </table>
  
  <span>
    <h2 style="color:#e0ffff; background-color:#66cdaa;">📜 Research Background, Current State, Objectives</h2><hr />
  </span>
  <blockquote>Tips: What is the background of the problem, what is the current state domestically and internationally, and what are the objectives?</blockquote>
  <p></p>
  <h3>⚙️ Background</h3>
  <p></p>
  <h3>💡 Current State</h3>
  <p></p>
  <h3>🚀 Objectives</h3>
  <p></p>
  
  <span>
    <h2 style="color:#20b2aa; background-color:#afeeee;">🔁 Research Content</h2><hr />
  </span>
  <p></p>
  <h3>🧩 Data</h3>
  <p></p>
  <h3>🚊 Research Foundation</h3>
  <p></p>
  <h3>💻 Technical Roadmap</h3>
  <p></p>
  <h3>👩🏻‍💻 Research Methods and Schemes</h3>
  <p></p>
  <h3>🔬 Experiment</h3>
  <p></p>
  <h3>📜 Conclusion</h3>
  <p></p>
  <h3>📚 Reference</h3>
  <p></p>
  
  <span>
    <h2 style="color:#004d99; background-color:#87cefa;">🤔 Personal Summary</h2><hr />
  </span>
  <blockquote>Tips: Personal gains and records?</blockquote>
  <p></p>
  <h3>🙋‍♀️ Key Records</h3>
  <p></p>
  <h3>📌 To be Resolved</h3>
  <p></p>
  <h3>💭 Thought Inspiration</h3>
  <p></p>
```

Zotero MainNote Template 中文版本在下面，仅仅把文字替换成了中文

```yaml
# Zotero MainNote Template (Chinese)
# @author [jackhanyuan](https://github.com/jackhanyuan)
# @source [zotero-better-plugin](https://github.com/jackhanyuan/zotero-better-plugin)
# This template is specifically for importing/sharing, using better 
# notes 'import from clipboard': copy the content and
# goto Zotero menu bar, click Edit->New Template from Clipboard.  
# Do not copy-paste this to better notes template editor directly.
name: "[Text]主笔记"
content: |-
  <span>
    <h1 style="color:#5686bf; background-color:#eef9fd;">主笔记标题✍</h1>
  </span>
  
  <table>
    <tr>
      <td style="color:#193c47; background-color:#dbeedd; padding:8px;">
        <b>👨‍🎓 作者：</b>
      </td>
    </tr>
    <tr>
      <td style="color:#193c47; background-color:#f3faf4; padding:8px;">
        <b>🌟 备注：</b>
      </td>
    </tr>
    <tr>
      <td style="color:#193c47; background-color:#dbeedd; padding:8px;">
        <b>🎯 方向分类：</b>
      </td>
    </tr>
    <tr>
      <td style="color:#193c47; background-color:#f3faf4; padding:8px;">
        <b>📅 笔记日期：</b>${new Date().toLocaleString()}
      </td>
    </tr>
  </table>
  
  <span>
    <h2 style="color:#e0ffff; background-color:#66cdaa;">📜 研究背景 现状 目标</h2><hr />
  </span>
  <blockquote>Tips: 问题提出的背景，国内外现状如何，目标是什么？</blockquote>
  <p></p>
  <h3>⚙️ 背景</h3>
  <p></p>
  <h3>💡 现状</h3>
  <p></p>
  <h3>🚀 目标</h3>
  <p></p>
  
  <span>
    <h2 style="color:#20b2aa; background-color:#afeeee;">🔁 研究内容</h2><hr />
  </span>
  <p></p>
  <h3>🧩 数据</h3>
  <p></p>
  <h3>🚊 研究基础</h3>
  <p></p>
  <h3>💻 技术路线</h3>
  <p></p>
  <h3>👩🏻‍💻 研究方法 方案</h3>
  <p></p>
  <h3>🔬 实验</h3>
  <p></p>
  <h3>📜 结论</h3>
  <p></p>
  <h3>📚 参考</h3>
  <p></p>
  
  <span>
    <h2 style="color:#004d99; background-color:#87cefa;">🤔 个人总结</h2><hr />
  </span>
  <blockquote>Tips: 个人收获与记录？</blockquote>
  <p></p>
  <h3>🙋‍♀️ 重点记录</h3>
  <p></p>
  <h3>📌 待解决</h3>
  <p></p>
  <h3>💭 思考启发</h3>
  <p></p>
```
