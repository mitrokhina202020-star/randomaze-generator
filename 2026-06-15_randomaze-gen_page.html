<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Генератор рандомайзера</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-grad: linear-gradient(135deg, #1f2937 0%, #111827 100%);
            --glass-bg: rgba(255, 255, 255, 0.05);
            --glass-border: rgba(255, 255, 255, 0.1);
            --accent: #8b5cf6;
            --accent-hover: #7c3aed;
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
            --danger: #ef4444;
            --success: #10b981;
            --card-bg: rgba(0, 0, 0, 0.2);
        }
        * { box-sizing: border-box; }
        body {
            font-family: 'Inter', sans-serif;
            background: var(--bg-grad);
            color: var(--text-main);
            margin: 0;
            min-height: 100vh;
            padding: 2rem;
        }
        .page-wrap { max-width: 900px; margin: 0 auto; }

        .header-bar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 2rem;
        }
        h1 { margin: 0; font-weight: 800; font-size: 1.8rem; }

        .glass-card {
            background: var(--glass-bg);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid var(--glass-border);
            border-radius: 16px;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
        }
        .section-title {
            font-weight: 700;
            font-size: 0.8rem;
            color: var(--text-muted);
            text-transform: uppercase;
            letter-spacing: 0.8px;
            margin: 0 0 1rem 0;
        }
        .settings-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1rem;
        }
        .form-group { margin: 0; }
        .form-group label {
            display: block;
            margin-bottom: 0.4rem;
            color: var(--text-muted);
            font-size: 0.85rem;
        }
        .form-control {
            width: 100%;
            padding: 0.65rem 0.9rem;
            background: rgba(0,0,0,0.3);
            border: 1px solid var(--glass-border);
            border-radius: 8px;
            color: var(--text-main);
            font-size: 0.95rem;
            font-family: inherit;
            outline: none;
            transition: border-color 0.2s;
        }
        .form-control:focus { border-color: var(--accent); }
        select.form-control option { background: #1e1b4b; color: white; }

        .btn {
            padding: 0.6rem 1.2rem;
            border-radius: 8px;
            border: none;
            font-weight: 600;
            cursor: pointer;
            font-size: 0.9rem;
            font-family: inherit;
            transition: all 0.2s;
            display: inline-flex;
            align-items: center;
            gap: 6px;
            text-decoration: none;
            color: var(--text-main);
        }
        .btn-primary { background: var(--accent); color: #fff; }
        .btn-primary:hover { background: var(--accent-hover); }
        .btn-ghost { background: rgba(255,255,255,0.08); border: 1px solid var(--glass-border); }
        .btn-ghost:hover { background: rgba(255,255,255,0.14); }
        .btn-danger { background: rgba(239,68,68,0.15); color: var(--danger); border: 1px solid rgba(239,68,68,0.3); }
        .btn-danger:hover { background: rgba(239,68,68,0.25); }
        .btn-generate { background: var(--success); color: #fff; font-size: 1rem; padding: 0.8rem 2.5rem; }
        .btn-generate:hover { background: #059669; }

        /* Project cards */
        .proj-card {
            background: var(--card-bg);
            border: 1px solid var(--glass-border);
            border-radius: 12px;
            padding: 1.2rem;
            margin-bottom: 1rem;
        }
        .proj-card-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 0.9rem;
        }
        .proj-num {
            font-weight: 700;
            font-size: 0.82rem;
            color: var(--accent);
            background: rgba(139,92,246,0.15);
            padding: 0.2rem 0.65rem;
            border-radius: 6px;
        }
        .title-input { margin-bottom: 0.7rem; }
        .collapse-btn {
            background: none;
            border: none;
            color: var(--text-muted);
            cursor: pointer;
            font-size: 0.75rem;
            padding: 2px 6px;
            border-radius: 4px;
            line-height: 1;
            transition: all 0.15s;
            flex-shrink: 0;
        }
        .collapse-btn:hover { background: rgba(255,255,255,0.1); color: var(--text-main); }
        .card-title-preview {
            color: var(--text-muted);
            font-size: 0.85rem;
            overflow: hidden;
            text-overflow: ellipsis;
            white-space: nowrap;
            flex: 1;
            min-width: 0;
        }
        .card-body { }
        .fab-add {
            position: fixed;
            bottom: 2rem;
            right: 2rem;
            z-index: 100;
            box-shadow: 0 4px 20px rgba(139,92,246,0.45);
            border-radius: 10px;
        }
        .toolbar {
            display: flex;
            gap: 4px;
            margin-bottom: 6px;
        }
        .toolbar-btn {
            background: rgba(255,255,255,0.06);
            border: 1px solid var(--glass-border);
            color: var(--text-muted);
            padding: 3px 11px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.82rem;
            font-family: inherit;
            font-weight: 600;
            transition: all 0.15s;
        }
        .toolbar-btn:hover { background: rgba(139,92,246,0.2); color: var(--text-main); border-color: var(--accent); }
        .desc-input {
            width: 100%;
            min-height: 160px;
            padding: 0.65rem 0.9rem;
            background: rgba(0,0,0,0.3);
            border: 1px solid var(--glass-border);
            border-radius: 8px;
            color: var(--text-main);
            font-size: 0.9rem;
            font-family: inherit;
            line-height: 1.65;
            outline: none;
            transition: border-color 0.2s;
            overflow-y: auto;
        }
        .desc-input:focus { border-color: var(--accent); }
        .desc-input:empty::before {
            content: attr(data-placeholder);
            color: var(--text-muted);
            pointer-events: none;
        }
        .desc-input h3 { margin: 0.5em 0 0.2em; font-size: 1em; font-weight: 700; }
        .desc-input ul, .desc-input ol { margin: 0.25em 0; padding-left: 1.5em; }
        .desc-input li { margin: 0.1em 0; }
        .desc-input p { margin: 0.3em 0; }
        .desc-input pre { background: rgba(0,0,0,0.35); padding: 0.8em 1em; border-radius: 6px; font-family: 'Consolas','Courier New',monospace; font-size: 0.85em; white-space: pre-wrap; overflow-x: auto; margin: 0.5em 0; }
        .desc-input code { background: rgba(0,0,0,0.25); padding: 0.1em 0.4em; border-radius: 3px; font-family: 'Consolas','Courier New',monospace; font-size: 0.9em; }

        /* Output */
        .output-area {
            min-height: 180px;
            font-family: 'Consolas', 'Courier New', monospace;
            font-size: 0.82rem;
            line-height: 1.5;
            resize: vertical;
            color: #a8ff78;
            background: rgba(0,0,0,0.55);
            border: 1px solid rgba(168,255,120,0.2);
        }
        .output-area:focus { border-color: rgba(168,255,120,0.45); }

        @media (max-width: 600px) {
            .settings-grid { grid-template-columns: 1fr; }
            body { padding: 1rem; }
        }
    </style>
</head>
<body>

<div class="page-wrap">
    <div class="header-bar">
        <h1>Генератор рандомайзера</h1>
    </div>

    <!-- Настройки -->
    <div class="glass-card">
        <p class="section-title">Настройки скрипта</p>
        <div class="settings-grid">
            <div class="form-group">
                <label>LESSON_ID — уникальный ID урока</label>
                <input type="text" id="lesson-id" class="form-control" placeholder="automation_3_project2">
            </div>
            <div class="form-group">
                <label>MAX_ATTEMPTS — лимит попыток</label>
                <input type="number" id="max-attempts" class="form-control" value="5" min="1" max="99">
            </div>
            <div class="form-group" style="grid-column:1/-1;">
                <label>SAVE_ENDPOINT — URL хука сохранения</label>
                <input type="text" id="save-endpoint" class="form-control" placeholder="https://...">
            </div>
        </div>
    </div>

    <!-- Проекты -->
    <div class="glass-card">
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:1rem;">
            <p class="section-title" style="margin:0;">Проекты</p>
            <label class="btn btn-ghost" style="cursor:pointer;font-size:0.85rem;">
                📂 Загрузить из Notion
                <input type="file" accept=".html" style="display:none;" onchange="importFromFile(this)">
            </label>
        </div>
        <div id="cards-wrap"></div>
        <div id="import-log" style="display:none;margin-bottom:0.75rem;font-size:0.85rem;color:var(--success);"></div>
        <div id="empty-state" style="text-align:center;padding:2rem;color:var(--text-muted);font-size:0.9rem;">
            Нажмите «+ Добавить проект» или загрузите HTML-экспорт из Notion
        </div>
    </div>

    <!-- Кнопка -->
    <div style="text-align:center;margin-bottom:1.5rem;">
        <button class="btn btn-generate" onclick="generate()">⚡ Сгенерировать скрипт</button>
    </div>

    <!-- Вывод 1 — рандомайзер с описаниями -->
    <div class="glass-card" id="output-block" style="display:none;">
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:1rem;">
            <p class="section-title" style="margin:0;">Готовый код — рандомайзер с описаниями</p>
            <button class="btn btn-ghost" onclick="copyOutput('output','copy-btn')" id="copy-btn" style="font-size:0.85rem;">📋 Скопировать</button>
        </div>
        <textarea id="output" class="form-control output-area" readonly></textarea>
    </div>

    <!-- Вывод 2 — простой список проектов -->
    <div class="glass-card" id="output-block-2" style="display:none;">
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:1rem;">
            <p class="section-title" style="margin:0;">Готовый код — простой список</p>
            <button class="btn btn-ghost" onclick="copyOutput('output-2','copy-btn-2')" id="copy-btn-2" style="font-size:0.85rem;">📋 Скопировать</button>
        </div>
        <textarea id="output-2" class="form-control output-area" readonly></textarea>
    </div>
</div>

<button class="btn btn-primary fab-add" onclick="addCard()">+ Добавить проект</button>

<script>
let cardCount = 0;

function addCard(title, desc) {
    title = title || '';
    desc  = desc  || '';
    cardCount++;
    const id = cardCount;

    const wrap = document.getElementById('cards-wrap');
    document.getElementById('empty-state').style.display = 'none';

    const div = document.createElement('div');
    div.className = 'proj-card';
    div.dataset.cid = id;
    div.innerHTML =
        '<div class="proj-card-header">' +
            '<div style="display:flex;align-items:center;gap:0.6rem;flex:1;min-width:0;">' +
                '<button class="collapse-btn" onmousedown="toggleCard(event,this)" title="Свернуть">▼</button>' +
                '<span class="proj-num">Проект #<span class="num-label"></span></span>' +
                '<span class="card-title-preview"></span>' +
            '</div>' +
            '<button class="btn btn-danger" onclick="removeCard(this)" style="padding:0.3rem 0.75rem;font-size:0.8rem;flex-shrink:0;">Удалить</button>' +
        '</div>' +
        '<div class="card-body">' +
            '<input type="text" class="form-control title-input" placeholder="Название проекта">' +
            '<div class="toolbar">' +
                '<button class="toolbar-btn" title="Жирный (Ctrl+B)" onmousedown="fmt(event,\'bold\')"><b>B</b></button>' +
                '<button class="toolbar-btn" title="Заголовок H3" onmousedown="fmt(event,\'h3\')">H3</button>' +
                '<button class="toolbar-btn" title="Список" onmousedown="fmt(event,\'li\')">• список</button>' +
            '</div>' +
            '<div class="desc-input" contenteditable="true" data-placeholder="Вставьте текст из Notion или начните печатать…"></div>' +
        '</div>';

    if (title) div.querySelector('.title-input').value = title;
    if (desc)  div.querySelector('.desc-input').innerHTML = desc;

    div.querySelector('.desc-input').addEventListener('paste', handlePaste);

    wrap.appendChild(div);
    renum();
}

function removeCard(btn) {
    btn.closest('.proj-card').remove();
    renum();
    if (!document.querySelectorAll('.proj-card').length) {
        document.getElementById('empty-state').style.display = '';
    }
}

function renum() {
    document.querySelectorAll('.proj-card').forEach((c, i) => {
        c.querySelector('.num-label').textContent = i + 1;
    });
}

function toggleCard(e, btn) {
    e.preventDefault();
    const card    = btn.closest('.proj-card');
    const body    = card.querySelector('.card-body');
    const preview = card.querySelector('.card-title-preview');
    const collapsed = body.style.display === 'none';
    if (collapsed) {
        body.style.display = '';
        btn.textContent    = '▼';
        btn.title          = 'Свернуть';
        preview.textContent = '';
    } else {
        body.style.display = 'none';
        btn.textContent    = '▶';
        btn.title          = 'Развернуть';
        preview.textContent = card.querySelector('.title-input').value || '(без названия)';
    }
}

function fmt(e, type) {
    e.preventDefault(); // не снимаем фокус с редактора
    if (type === 'bold') {
        document.execCommand('bold');
    } else if (type === 'h3') {
        document.execCommand('formatBlock', false, 'h3');
    } else if (type === 'li') {
        document.execCommand('insertUnorderedList');
    }
}

function handlePaste(e) {
    e.preventDefault();
    const html  = e.clipboardData.getData('text/html');
    const plain = e.clipboardData.getData('text/plain');
    const result = html ? sanitizeHtml(html) : escHtml(plain).replace(/\n/g, '<br>');
    document.execCommand('insertHTML', false, result);
}

function sanitizeHtml(html) {
    const tmp = document.createElement('div');
    tmp.innerHTML = html;
    return walkNodes(tmp);
}

function walkNodes(node) {
    let out = '';
    for (const child of node.childNodes) {
        if (child.nodeType === 3) { out += escHtml(child.textContent); continue; }
        if (child.nodeType !== 1) continue;
        const tag = child.tagName.toLowerCase();
        const inner = walkNodes(child);
        if (['strong','b'].includes(tag))                     { out += '<strong>' + inner + '</strong>'; }
        else if (['em','i'].includes(tag))                    { out += '<em>' + inner + '</em>'; }
        else if (['h1','h2','h3','h4','h5','h6'].includes(tag)) { out += '<h3 style="margin-top:1.2em;margin-bottom:0.2em;">' + inner + '</h3>'; }
        else if (tag === 'ul')                                 { out += '<ul>' + inner + '</ul>'; }
        else if (tag === 'ol') {
            const s = parseInt(child.getAttribute('start'));
            out += (s > 1 ? '<ol start="' + s + '">' : '<ol>') + inner + '</ol>';
        }
        else if (tag === 'li')                                 { out += '<li>' + inner + '</li>'; }
        else if (tag === 'br')                                 { out += '<br>'; }
        else if (tag === 'pre') {
            out += '<pre style="background:rgba(0,0,0,0.35);padding:0.8em 1em;border-radius:6px;overflow-x:auto;font-family:monospace;font-size:0.85em;white-space:pre-wrap;margin:0.5em 0;">' + escHtml(child.textContent) + '</pre>';
        }
        else if (tag === 'code') {
            out += '<code style="background:rgba(0,0,0,0.25);padding:0.1em 0.4em;border-radius:3px;font-family:monospace;font-size:0.9em;">' + escHtml(child.textContent) + '</code>';
        }
        else if (tag === 'p') {
            out += inner + (inner.trim() ? '<br>' : '');
        } else if (tag === 'div') {
            out += inner;
        } else if (tag === 'span') {
            const style = child.getAttribute('style') || '';
            if (/font-weight\s*:\s*(700|bold)/i.test(style))  { out += '<strong>' + inner + '</strong>'; }
            else                                               { out += inner; }
        } else { out += inner; }
    }
    return out;
}

function escHtml(s) {
    return s.replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;');
}

function importFromFile(input) {
    const file = input.files[0];
    if (!file) return;

    const reader = new FileReader();
    reader.onload = function(e) {
        const parser = new DOMParser();
        const doc    = parser.parseFromString(e.target.result, 'text/html');

        // Notion экспортирует ТЗ как <details> тоглы
        const toggles = doc.querySelectorAll('details');
        let added = 0;

        if (toggles.length > 0) {
            toggles.forEach(detail => {
                const summary = detail.querySelector('summary');
                if (!summary) return;
                const title   = summary.textContent.trim();
                const body    = detail.querySelector('.indented');
                const desc    = body ? sanitizeHtml(body.innerHTML) : '';
                addCard(title, desc);
                added++;
            });
        } else {
            // Нет тоглов — вся страница как один проект
            const pageTitle = doc.querySelector('.page-title');
            const pageBody  = doc.querySelector('.page-body');
            if (pageBody) {
                const title = pageTitle ? pageTitle.textContent.trim() : file.name.replace(/\.html$/i,'');
                const desc  = sanitizeHtml(pageBody.innerHTML);
                addCard(title, desc);
                added++;
            }
        }

        input.value = '';

        const log = document.getElementById('import-log');
        if (added > 0) {
            document.getElementById('empty-state').style.display = 'none';
            log.textContent = '✓ Загружено проектов: ' + added;
            log.style.display = '';
            setTimeout(() => { log.style.display = 'none'; }, 3000);
        } else {
            alert('Проекты не найдены. Убедитесь, что файл — Notion HTML-экспорт со страницы с тоглами.');
        }
    };
    reader.readAsText(file, 'utf-8');
}

function normalizeEditorHtml(html) {
    // Браузер иногда оборачивает строки в <div> — превращаем в <br>
    return html
        .replace(/<div><br><\/div>/gi, '<br>')
        .replace(/<div>([\s\S]*?)<\/div>/gi, '$1<br>')
        .replace(/(<br>\s*){3,}/gi, '<br><br>')
        .trim();
}

function generate() {
    const lessonId    = document.getElementById('lesson-id').value.trim();
    const maxAttempts = parseInt(document.getElementById('max-attempts').value) || 5;
    const saveEndpoint = document.getElementById('save-endpoint').value.trim();
    const cards = document.querySelectorAll('.proj-card');

    if (!lessonId)    { alert('Заполните LESSON_ID'); return; }
    if (!cards.length) { alert('Добавьте хотя бы один проект'); return; }

    const projLines = [];
    cards.forEach(card => {
        const t = card.querySelector('.title-input').value;
        const d = normalizeEditorHtml(card.querySelector('.desc-input').innerHTML);
        projLines.push(
            '    {\n' +
            '      title: ' + JSON.stringify(t) + ',\n' +
            '      desc: '  + JSON.stringify(d) + '\n' +
            '    }'
        );
    });

    // Скрипт 1 — рандомайзер с описаниями
    const out = buildOutput(lessonId, maxAttempts, saveEndpoint, projLines.join(',\n'));
    const ta  = document.getElementById('output');
    ta.value  = out;
    ta.style.height = 'auto';
    ta.style.height = Math.min(640, ta.scrollHeight) + 'px';
    document.getElementById('output-block').style.display = '';

    // Скрипт 2 — простой список
    const titles = [];
    cards.forEach((card, i) => {
        const t = card.querySelector('.title-input').value;
        titles.push('  ' + JSON.stringify('Проект ' + (i + 1) + ': ' + t));
    });
    const out2 = buildSimpleOutput(titles);
    const ta2  = document.getElementById('output-2');
    ta2.value  = out2;
    ta2.style.height = 'auto';
    ta2.style.height = Math.min(480, ta2.scrollHeight) + 'px';
    document.getElementById('output-block-2').style.display = '';

    document.getElementById('output-block').scrollIntoView({ behavior: 'smooth', block: 'start' });
}

function copyOutput(taId, btnId) {
    const ta  = document.getElementById(taId);
    const btn = document.getElementById(btnId);
    ta.select();
    document.execCommand('copy');
    btn.textContent = '✓ Скопировано';
    setTimeout(() => btn.textContent = '📋 Скопировать', 2000);
}

// ─── Простой список ─────────────────────────────────────────────────────────
function buildSimpleOutput(titles) {
    const L = [];
    L.push('<script>');
    L.push('const projects = [');
    L.push(titles.join(',\n'));
    L.push('];');
    L.push('');
    L.push('let currentProjectIndex = null;');
    L.push('let rerollCount = 3;');
    L.push('');
    L.push("const projectDisplay = document.getElementById('project-display');");
    L.push("const getProjectBtn  = document.getElementById('get-project-btn');");
    L.push("const rerollBtn      = document.getElementById('reroll-btn');");
    L.push("const rerollCountSpan = document.getElementById('reroll-count');");
    L.push('');
    L.push('function getRandomProjectIndex(excludeIndex) {');
    L.push('  let idx;');
    L.push('  do { idx = Math.floor(Math.random() * projects.length); }');
    L.push('  while (projects.length > 1 && idx === excludeIndex);');
    L.push('  return idx;');
    L.push('}');
    L.push('');
    L.push('getProjectBtn.onclick = function() {');
    L.push('  currentProjectIndex = getRandomProjectIndex(null);');
    L.push('  projectDisplay.textContent = projects[currentProjectIndex];');
    L.push('  rerollCount = 3;');
    L.push('  rerollCountSpan.textContent = rerollCount;');
    L.push('  rerollBtn.disabled = false;');
    L.push('  getProjectBtn.disabled = true;');
    L.push('};');
    L.push('');
    L.push('rerollBtn.onclick = function() {');
    L.push('  if (rerollCount <= 0) return;');
    L.push('  currentProjectIndex = getRandomProjectIndex(currentProjectIndex);');
    L.push('  projectDisplay.textContent = projects[currentProjectIndex];');
    L.push('  rerollCount--;');
    L.push('  rerollCountSpan.textContent = rerollCount;');
    L.push('  if (rerollCount === 0) rerollBtn.disabled = true;');
    L.push('};');
    L.push('<\/script>');
    return L.join('\n');
}

// ─── Сборка готового скрипта ────────────────────────────────────────────────
// Все строки пушатся как обычные JS-строки → backtick и ${} внутри них
// не интерпретируются движком и попадают в вывод как есть.
// Для вывода пользовательских данных используется JSON.stringify() —
// это гарантирует безопасность любого текста (кавычки, слеши, переносы).
function buildOutput(lessonId, maxAttempts, saveEndpoint, projects) {
    const useGet = false;
    const L = [];

    // HTML-блок
    L.push('<!-- === Рандомайзер итогового проекта (' + maxAttempts + ' попыток | история | сохранить) === -->');
    L.push('<div id="project-randomizer" class="rcard">');
    L.push('  <h3>Ваш проект</h3>');
    L.push('');
    L.push('  <div id="project-result" class="result">');
    L.push('    <span class="placeholder">Нажмите кнопку, чтобы получить проект</span>');
    L.push('  </div>');
    L.push('');
    L.push('  <button id="roll-btn"    class="roll">Получить проект</button>');
    L.push('  <button id="history-btn" class="roll" style="margin-left:12px;">История</button>');
    L.push('  <button id="save-btn"    class="roll" style="margin-left:12px;" disabled>Сохранить</button>');
    L.push('  <small  id="tries-left"  class="hint"></small>');
    L.push('');
    L.push('  <div id="history-wrap" style="display:none;margin-top:24px;">');
    L.push('    <h4 style="text-align:center;margin-bottom:12px;">Ранее выбранные проекты</h4>');
    L.push('    <div id="history-list"></div>');
    L.push('  </div>');
    L.push('</div>');
    L.push('');
    L.push('<script>');

    // Блок настроек
    L.push('/* ═══ 0. НАСТРОЙКИ ════════════════════════════════════════════ */');
    L.push('const LESSON_ID     = ' + JSON.stringify(lessonId) + ';               // уникальный id урока');
    L.push('const MAX_ATTEMPTS  = ' + maxAttempts + ';                       // лимит попыток');
    L.push('const SAVE_ENDPOINT = ' + JSON.stringify(saveEndpoint) + ';');
    L.push('const USE_GET       = ' + useGet + ';                   // true → GET-запрос, false → POST JSON');
    L.push("const USER_ID       = '{uid }';             // GetCourse подставит числовой uid");
    L.push('/* ═══════════════════════════════════════════════════════════════ */');
    L.push('');

    // IIFE — начало + ключи localStorage
    L.push('(() => {');
    L.push('  /* 1. Ключи localStorage (уникальны для LESSON_ID) */');
    L.push('  const PREFIX      = `gc_project_${LESSON_ID}_`;');
    L.push("  const ATTEMPT_KEY = PREFIX + 'attempts';");
    L.push("  const CHOICE_KEY  = PREFIX + 'choice';");
    L.push("  const HISTORY_KEY = PREFIX + 'history';");
    L.push("  const USED_KEY    = PREFIX + 'used';");
    L.push("  const SAVED_KEY   = PREFIX + 'saved';        // флаг «отправлено»");
    L.push('');

    // DOM
    L.push('  /* 2. DOM */');
    L.push("  const btnRoll   = document.getElementById('roll-btn');");
    L.push("  const btnHist   = document.getElementById('history-btn');");
    L.push("  const btnSave   = document.getElementById('save-btn');");
    L.push("  const resultBox = document.getElementById('project-result');");
    L.push("  const hint      = document.getElementById('tries-left');");
    L.push("  const histWrap  = document.getElementById('history-wrap');");
    L.push("  const histList  = document.getElementById('history-list');");
    L.push('');

    // Проекты
    L.push('  /* 3. Полный список проектов */');
    L.push('  const projects = [');
    L.push(projects);
    L.push('  ];');
    L.push('');

    // Состояние
    L.push('  /* 4. Состояние */');
    L.push('  let attempts = Number(localStorage.getItem(ATTEMPT_KEY)) || 0;');
    L.push("  let history  = JSON.parse(localStorage.getItem(HISTORY_KEY) || '[]');");
    L.push("  let used     = JSON.parse(localStorage.getItem(USED_KEY)    || '[]');");
    L.push('  const savedChoice  = localStorage.getItem(CHOICE_KEY);');
    L.push("  const alreadySaved = localStorage.getItem(SAVED_KEY) === '1';");
    L.push('');
    L.push('  if (savedChoice) resultBox.innerHTML = savedChoice;');
    L.push('  btnSave.disabled = !savedChoice || alreadySaved;');
    L.push("  if (alreadySaved) btnSave.textContent = '✓ Сохранено';");
    L.push('');
    L.push('  renderHistory();');
    L.push('  updateUI();');
    L.push('');

    // Кнопка «Получить / Поменять»
    L.push("  /* 5. Получить / Поменять */");
    L.push("  btnRoll.addEventListener('click', () => {");
    L.push('    if (attempts >= MAX_ATTEMPTS) return;');
    L.push('');
    L.push('    const available = projects');
    L.push('      .map((p,i)=>({...p, idx:i}))');
    L.push('      .filter(p => !used.includes(p.idx));');
    L.push('');
    L.push('    if (!available.length) return;');
    L.push('');
    L.push('    const pick = available[Math.floor(Math.random()*available.length)];');
    L.push('    const html = formatProject(pick);');
    L.push('');
    L.push('    resultBox.innerHTML = html;');
    L.push('    btnSave.disabled = false;');
    L.push("    btnSave.textContent = 'Сохранить';");
    L.push("    localStorage.removeItem(SAVED_KEY);          // сбросили метку");
    L.push('');
    L.push('    used.push(pick.idx);');
    L.push('    history.push(html);');
    L.push('');
    L.push('    localStorage.setItem(CHOICE_KEY,  html);');
    L.push('    localStorage.setItem(USED_KEY,    JSON.stringify(used));');
    L.push('    localStorage.setItem(HISTORY_KEY, JSON.stringify(history));');
    L.push('    localStorage.setItem(ATTEMPT_KEY, ++attempts);');
    L.push('');
    L.push('    renderHistory();');
    L.push('    updateUI();');
    L.push('  });');
    L.push('');

    // История
    L.push("  /* 6. История */");
    L.push("  btnHist.addEventListener('click', () => {");
    L.push("    histWrap.style.display = histWrap.style.display === 'none' ? 'block' : 'none';");
    L.push('  });');
    L.push('');

    // Сохранить
    L.push("  /* 7. Сохранить */");
    L.push("  btnSave.addEventListener('click', async () => {");
    L.push('    if (btnSave.disabled) return;');
    L.push("    const title = resultBox.querySelector('.proj-title')?.textContent || '';");
    L.push('    if (!title) return;');
    L.push('');
    L.push("    const _clone = resultBox.cloneNode(true);");
    L.push("    const _tEl = _clone.querySelector('.proj-title');");
    L.push("    if (_tEl) { if (_tEl.nextSibling?.nodeName==='BR') _tEl.nextSibling.remove(); _tEl.remove(); }");
    L.push("    const desc = _clone.innerHTML.trim();");
    L.push('');
    L.push('    const payload = {');
    L.push('      lesson_id     : LESSON_ID,');
    L.push('      user_id       : USER_ID,');
    L.push('      project_title : title,');
    L.push('      project_desc  : desc,');
    L.push('      attempts_left : MAX_ATTEMPTS - attempts,');
    L.push('      timestamp     : new Date().toISOString()');
    L.push('    };');
    L.push('');
    L.push('    try {');
    L.push('      if (USE_GET) {');
    L.push('        const qs = new URLSearchParams(payload).toString();');
    L.push("        await fetch(`${SAVE_ENDPOINT}?${qs}`, { mode:'cors' });");
    L.push('      } else {');
    L.push('        await fetch(SAVE_ENDPOINT, {');
    L.push("          method  : 'POST',");
    L.push("          mode    : 'cors',");
    L.push("          headers : { 'Content-Type':'application/json' },");
    L.push('          body    : JSON.stringify(payload)');
    L.push('        });');
    L.push('      }');
    L.push("      btnSave.textContent = '✓ Сохранено';");
    L.push('      btnSave.disabled = true;');
    L.push("      localStorage.setItem(SAVED_KEY, '1');     // пометили «уже отправлено»");
    L.push('    } catch (err) {');
    L.push('      console.error(err);');
    L.push("      btnSave.textContent = 'Ошибка';");
    L.push('    }');
    L.push('  });');
    L.push('');

    // Вспомогательные функции
    L.push("  /* 8. Вспомогательные функции */");
    L.push('  function updateUI(){');
    L.push('    const left = MAX_ATTEMPTS - attempts;');
    L.push("    hint.textContent   = left>0 ? `Осталось попыток: ${left}` : 'Попытки закончились.';");
    L.push('    btnRoll.disabled   = left===0;');
    L.push("    btnRoll.textContent= attempts===0 ? 'Получить проект' : 'Поменять';");
    L.push("    btnHist.disabled   = history.length===0;");
    L.push('  }');
    L.push('');
    L.push('  function renderHistory(){');
    L.push('    histList.innerHTML = history.map((item,i)=>`');
    L.push('      <div class="history-item">');
    L.push('        <div style="font-weight:500;margin-bottom:8px;">#${i+1}</div>');
    L.push('        ${item}');
    L.push('        <button class="select-btn" data-idx="${i}">Выбрать</button>');
    L.push('      </div>`');
    L.push('    ).join(\'<hr class="history-sep">\');');
    L.push('');
    L.push("    document.querySelectorAll('.select-btn').forEach(btn=>{");
    L.push("      btn.addEventListener('click',e=>{");
    L.push('        const idx  = +e.currentTarget.dataset.idx;');
    L.push('        const html = history[idx];');
    L.push('        resultBox.innerHTML = html;');
    L.push('');
    L.push('        btnSave.disabled = false;');
    L.push("        btnSave.textContent = 'Сохранить';");
    L.push("        localStorage.removeItem(SAVED_KEY);     // сбросили флаг");
    L.push('');
    L.push('        localStorage.setItem(CHOICE_KEY, html);');
    L.push('      });');
    L.push('    });');
    L.push('  }');
    L.push('');
    L.push('  function escT(s){ return s.replace(/&/g,"&amp;").replace(/</g,"&lt;"); }');
    L.push('  function formatProject(p){');
    L.push('    return \'<strong class="proj-title">\' + escT(p.title) + \'</strong><br>\' + p.desc;');
    L.push('  }');
    L.push('})();');
    L.push('<\/script>');

    return L.join('\n');
}
</script>

</body>
</html>
