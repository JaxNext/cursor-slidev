---
title: Jax - Cursor Meetup 广州
info: |
  20 July 2025 · 2 PM – 6 PM · 广州
class: bg-[#0F0F0F] text-white text-center font-inter
mdc: true
theme: slidev-theme-cursor
layout: cover
---

<GlowBackground>
  <div class="flex flex-col items-center justify-center h-full">
    <h1 class="tracking-tight text-white">Cursor 武装升级</h1>
    <h2 class="tracking-tight text-white">MCP 应用 & 自建</h2>
  </div>
</GlowBackground>

---

<div class="overline text-[14px] font-medium tracking-wider uppercase text-white/80 mb-2">Speaker</div>
<div class="max-w-xl mx-auto mt-20">
  <div class="font-semibold text-white mr-10 text-right">
    <div class="text-[36px]">钱俊颖</div>
    <div class="text-[24px]">Jax</div>
  </div>
  <div class="text-left text-white/80">
    <div class="mb-2">ShareWorks 前端架构师</div>
    <div class="mb-2">Web GDE</div>
    <div class="mb-2">掘金优秀创作者</div>
  </div>
</div>

---

<div class="overline text-[14px] font-medium tracking-wider uppercase text-white/80 mb-2">Agenda</div>
<div class="card bg-[#171717] border border-[#252525] rounded-[4px] p-6 max-w-xl mx-auto mt-10">
  <ol class="text-left text-white/80 list-decimal list-inside">
    <li>MCP 简介</li>
    <li>Cursor 中的 MCP</li>
    <li>MCP Server 开发</li>
  </ol>
</div>

---

<div class="overline text-[14px] font-medium tracking-wider uppercase text-white/80 mb-2">MCP 简介 - 概念</div>
<h1 class="flex items-center justify-center font-semibold text-white/80 mt-35">模型<span class="text-[#40e0d0]">上下文</span>协议</h1>
<h3 class="flex items-center justify-center font-semibold text-white/80 mt-2 mb-5">Model Context Protocol</h3>
<div class="flex items-center justify-center font-semibold text-white/50 mt-2">约定统一的格式，来构成模型上下文里的 Data、Tools</div>
<div class="flex items-center justify-center font-semibold text-white/50 mt-2">增强通用能力，减少信息壁垒</div>

---

<div class="overline text-[14px] font-medium tracking-wider uppercase text-white/80 mb-2">MCP 简介 - 用途</div>
<img src="./assets/architecture.jpeg" alt="MCP usage" class="w-[70%] mx-auto mt-10 rounded-[4px] shadow-[0_20px_40px_rgba(0,0,0,0.5)]" />

---

<div class="overline text-[14px] font-medium tracking-wider uppercase text-white/80 mb-2">MCP 简介 - 生态</div>
  <div class="flex flex-col items-center justify-center mt-15 mb-10">
    <div class="text-[72px] font-semibold text-white/80">6800+</div>
    <div class="text-[24px] font-semibold text-white/50">MCP servers</div>
  </div>
  <div class="flex items-center justify-center">
    <div class="card bg-[#171717] border border-[#252525] rounded-[4px] p-6 max-w-xl">
      <a href="https://glama.ai/mcp" target="_blank" class="underline">Glama</a>
    </div>
    <div class="card bg-[#171717] border border-[#252525] rounded-[4px] p-6 max-w-xl">
      <a href="https://mcp.so/" target="_blank" class="underline">MCP.so</a>
    </div>
    <div class="card bg-[#171717] border border-[#252525] rounded-[4px] p-6 max-w-xl">
      <a href="https://www.pulsemcp.com/" target="_blank" class="underline">PulseMCP</a>
    </div>
  </div>

---

<div class="overline text-[14px] font-medium tracking-wider uppercase text-white/80 mb-2">MCP in Cursor - 官方市场</div>
<h3 class="flex flex-col items-center justify-center font-semibold text-white/80"><a href="https://docs.cursor.com/tools/mcp" target="_blank" class="underline my-10">https://docs.cursor.com/tools/mcp</a></h3>
<img src="./assets/tools.jpeg"class="w-[70%] mx-auto rounded-[4px] shadow-[0_20px_40px_rgba(0,0,0,0.5)]" />

---

<div class="overline text-[14px] font-medium tracking-wider uppercase text-white/80 mb-2">MCP in Cursor - 使用</div>
  <img src="./assets/mcp-in-cursor.jpeg" alt="MCP in Cursor" class="w-[70%] mx-auto mt-10 rounded-[4px] shadow-[0_20px_40px_rgba(0,0,0,0.5)]" />

---

<div class="overline text-[14px] font-medium tracking-wider uppercase text-white/80 mb-2">MCP Server 开发 - 场景</div>
<div class="card bg-[#171717] border border-[#252525] rounded-[4px] p-6 max-w-xl mx-auto mt-10 flex flex-col space-y-4">
  <div class="self-start max-w-[75%] bg-[#252525]/50 rounded-lg p-3">
    <div class="text-xs text-white/60 mb-1">产品经理</div>
    <p class="text-white/80">”给我 CMS 新增一个表单页，录入用户信息。“</p>
  </div>
  <div class="self-start max-w-[75%] bg-[#252525]/50 rounded-lg p-3">
    <div class="text-xs text-white/60 mb-1">后端开发</div>
    <p class="text-white/80">”接口文档写好了，放在接口平台上了。“</p>
  </div>
  <div class="self-end max-w-[75%] bg-[#40e0d0]/20 rounded-lg p-3">
    <div class="text-xs text-white/60 mb-1 text-right">你</div>
    <p class="text-white/80 text-right">”喵喵喵？“</p>
  </div>
</div>

---

<div class="overline text-[14px] font-medium tracking-wider uppercase text-white/80 mb-2">MCP Server 开发 - 效果演示</div>
<div class="rounded-[4px] border border-[#252525] bg-[#171717] p-4 max-w-2xl mx-auto flex flex-col items-center mt-10">
  <span class="text-[#6E6E6E]">Todo: screenshot.gif</span>
</div>

---

<div class="overline text-[14px] font-medium tracking-wider uppercase text-white/80 mb-2">MCP Server 开发 - 核心代码</div>
<div class="mt-10">

  ```js
  import { McpServer, ResourceTemplate } from "@modelcontextprotocol/sdk/server/mcp.js";
  import { StdioServerTransport } from "@modelcontextprotocol/sdk/server/stdio.js";
  import { z } from "zod";

  const server = new McpServer({
    name: 'Torna',
    version: '1.0.0'
  })
  server.tool(
    'torna',
    { docId: z.string() },
    function () {
      // 获取 & 组装数据……
    }
  )

  const transport = new StdioServerTransport();
  server.connect(transport);
  ```

</div>

---

<div class="overline text-[14px] font-medium tracking-wider uppercase text-white/80 mb-2">MCP Server 开发 - 安装</div>
<div class="mt-10">

  ```json
  {
    "mcpServers": {
      ...
      "Torna": {
        "command": "node",
        "args": [
          "Torna.js"
        ]
      }
    }
  }
  ```

</div>

---

<GlowBackground>
  <div class="flex flex-col items-center justify-center h-full">
    <h1 class="text-6xl md:text-8xl font-extrabold tracking-tight text-white">感谢倾听!</h1>
    <h2 class="text-6xl md:text-8xl font-extrabold tracking-tight text-white">欢迎交流</h2>
    <img src="./assets/wechat.png" alt="QR Code" class="w-[200px] mx-auto mt-10 rounded-[4px] shadow-[0_20px_40px_rgba(0,0,0,0.5)]" />
  </div>

</GlowBackground>
