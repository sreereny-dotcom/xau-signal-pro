<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>XAU Intraday Pro — Live Intraday Gold Signals</title>
    <style>
        *{margin:0;padding:0;box-sizing:border-box}
        body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif;background:#0a0e17;color:#e0e6f0;min-height:100vh;padding:16px}
        .container{max-width:480px;margin:0 auto}
        .header{text-align:center;padding:12px 0 20px}
        .header h1{font-size:22px;font-weight:700;background:linear-gradient(135deg,#f7931a,#ffd700);-webkit-background-clip:text;-webkit-text-fill-color:transparent}
        .header .subtitle{font-size:12px;color:#6b7280;margin-top:4px}
        .header .badge-row{margin-top:6px}
        .badge{display:inline-block;font-size:9px;padding:2px 10px;border-radius:20px;margin:0 3px}
        .badge.live{background:#10b981;color:white;animation:pulse 2s infinite}
        .badge.intraday{background:#f59e0b;color:#0a0e17}
        .badge.notif{background:#3b82f6;color:white;cursor:pointer}
        @keyframes pulse{0%,100%{opacity:1}50%{opacity:0.6}}
        .price-card{background:linear-gradient(135deg,#1a1f2e,#0f1420);border-radius:16px;padding:20px;text-align:center;margin-bottom:12px;border:1px solid #1e293b}
        .price-label{font-size:11px;color:#6b7280;text-transform:uppercase;letter-spacing:1px}
        .price-value{font-size:38px;font-weight:700;margin:6px 0;font-variant-numeric:tabular-nums}
        .price-value.up{color:#10b981}.price-value.down{color:#ef4444}
        .price-change{font-size:13px;font-weight:600}
        .price-change.up{color:#10b981}.price-change.down{color:#ef4444}
        .price-details{display:flex;justify-content:space-between;margin-top:12px;padding-top:12px;border-top:1px solid #1e293b}
        .price-details div{text-align:center;flex:1}
        .price-details .label{font-size:9px;color:#6b7280}
        .price-details .value{font-size:13px;font-weight:600;margin-top:2px}
        .signal-card{background:linear-gradient(135deg,#1a1f2e,#0f1420);border-radius:16px;padding:20px;text-align:center;margin-bottom:12px;border:1px solid #1e293b}
        .signal-label{font-size:11px;color:#6b7280;text-transform:uppercase;letter-spacing:1px;margin-bottom:6px}
        .signal-value{font-size:28px;font-weight:800;padding:6px 0}
        .signal-value.buy{color:#10b981}.signal-value.sell{color:#ef4444}.signal-value.hold{color:#f59e0b}
        .signal-confidence{font-size:13px;color:#6b7280;margin-top:4px}
        .signal-reason{font-size:11px;color:#9ca3af;margin-top:10px;padding:6px 10px;background:#0f1420;border-radius:8px}
        .signal-icon{font-size:40px;margin-bottom:6px}
        .signal-changed-badge{display:inline-block;background:#ef4444;color:white;font-size:9px;padding:2px 8px;border-radius:20px;margin-left:6px;animation:pulse 1s infinite}
        .action-badge{display:inline-block;font-size:14px;font-weight:700;padding:4px 16px;border-radius:8px;margin:8px 0}
        .action-badge.buy{background:#10b981;color:white}.action-badge.sell{background:#ef4444;color:white}.action-badge.wait{background:#374151;color:#9ca3af}
        .indicator-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:6px;margin-bottom:12px}
        .indicator-card{background:#1a1f2e;border-radius:10px;padding:10px;text-align:center;border:1px solid #1e293b}
        .indicator-card .ind-label{font-size:9px;color:#6b7280}
        .indicator-card .ind-value{font-size:14px;font-weight:600;margin-top:3px}
        .indicator-card .ind-value.ema-fast{color:#60a5fa}.indicator-card .ind-value.ema-slow{color:#a78bfa}
        .indicator-card .ind-value.sma{color:#fb923c}.indicator-card .ind-value.rsi{color:#34d399}
        .indicator-card .ind-value.rsi.overbought{color:#ef4444}.indicator-card .ind-value.rsi.oversold{color:#10b981}
        .trade-card{background:linear-gradient(135deg,#1e293b,#0f172a);border-radius:16px;padding:16px;margin-bottom:12px;border:1px solid #334155}
        .trade-card h3{font-size:13px;color:#f59e0b;margin-bottom:10px;text-align:center}
        .trade-row{display:flex;justify-content:space-between;padding:5px 0;font-size:12px;border-bottom:1px solid #1e293b}
        .trade-row:last-child{border-bottom:none}
        .trade-row .label{color:#9ca3af}.trade-row .value{font-weight:600}
        .trade-row .value.buy{color:#10b981}.trade-row .value.sell{color:#ef4444}
        .next-update{text-align:center;font-size:10px;color:#374151;margin-bottom:12px;padding:6px}
        .history-card{background:#1a1f2e;border-radius:16px;padding:16px;border:1px solid #1e293b}
        .history-card h3{font-size:13px;color:#9ca3af;margin-bottom:10px}
        .history-item{display:flex;justify-content:space-between;align-items:center;padding:6px 0;border-bottom:1px solid #1e293b;font-size:12px}
        .history-item:last-child{border-bottom:none}
        .history-time{color:#6b7280;font-size:10px}
        .history-signal{font-weight:700;font-size:11px}
        .history-signal.buy{color:#10b981}.history-signal.sell{color:#ef4444}.history-signal.hold{color:#f59e0b}
        .history-price{color:#9ca3af;font-size:11px}.history-conf{color:#6b7280;font-size:10px}
        .history-changed{color:#ef4444;font-size:9px;margin-left:2px}
        .loading{text-align:center;padding:40px;color:#6b7280}
        .loading .spinner{width:36px;height:36px;border:3px solid #1e293b;border-top-color:#f7931a;border-radius:50%;animation:spin 1s linear infinite;margin:0 auto 10px}
        @keyframes spin{to{transform:rotate(360deg)}}
        .footer{text-align:center;padding:16px 0 8px;font-size:9px;color:#374151}
    </style>
</head>
<body>
<div class="container">
    <div class="header">
        <h1>⚡ XAU Intraday Pro</h1>
        <div class="subtitle">Live Intraday Gold Signals • 5-min Updates</div>
        <div class="badge-row">
            <span class="badge live">● LIVE</span>
            <span class="badge intraday">INTRADAY</span>
            <span class="badge notif" onclick="requestNotification()">🔔 Alerts</span>
        </div>
    </div>
    <div id="nextUpdate" class="next-update">Next update in: --:--</div>
    <div id="app"><div class="loading"><div class="spinner"></div>Loading intraday signals...</div></div>
    <div class="footer"><p>⚠️ Intraday trading is high risk. Never risk more than you can afford to lose.</p><p>Past performance does not guarantee future results.</p></div>
</div>
<script>
const API_BASE='/api';
let lastSignal = null;
let countdownInterval = null;
let nextUpdateTime = null;

function formatPrice(p){return p?p.toLocaleString('en-US',{minimumFractionDigits:2,maximumFractionDigits:2}):'--'}
function getSignalEmoji(s){if(s.includes('BUY'))return'🚀';if(s.includes('SELL'))return'📉';return'⏸️'}
function getSignalClass(s){if(s.includes('BUY'))return'buy';if(s.includes('SELL'))return'sell';return'hold'}
function getActionClass(a){if(a.includes('BUY'))return'buy';if(a.includes('SELL'))return'sell';return'wait'}

function requestNotification() {
    if (!("Notification" in window)) { alert("Notifications not supported"); return; }
    if (Notification.permission === "granted") {
        new Notification("⚡ XAU Intraday Pro", { body: "Notifications enabled! You'll be alerted on signal changes.", icon: "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ctext y='80' font-size='80'%3E⚡%3C/text%3E%3C/svg%3E" });
    } else if (Notification.permission !== "denied") {
        Notification.requestPermission().then(perm => {
            if (perm === "granted") new Notification("⚡ XAU Intraday Pro", { body: "Notifications enabled!" });
        });
    }
}

function sendNotification(title, body) {
    if (!("Notification" in window)) return;
    if (Notification.permission === "granted") {
        new Notification(title, { body: body, icon: "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ctext y='80' font-size='80'%3E⚡%3C/text%3E%3C/svg%3E" });
    }
}

function updateCountdown() {
    if (!nextUpdateTime) return;
    const now = Date.now();
    const diff = Math.max(0, Math.floor((nextUpdateTime - now) / 1000));
    const mins = Math.floor(diff / 60);
    const secs = diff % 60;
    document.getElementById('nextUpdate').textContent = `Next update in: ${String(mins).padStart(2,'0')}:${String(secs).padStart(2,'0')}`;
    if (diff === 0) document.getElementById('nextUpdate').textContent = '🔄 Updating now...';
}

function render(d) {
    const s = d.signal;
    const p = d.price;
    const h = d.history || [];
    const t = d.trade || {};
    const changed = d.signal_changed;
    const pc = p.change >= 0 ? 'up' : 'down';
    const cs = p.change >= 0 ? '+' : '';
    const sc = getSignalClass(s.signal);
    const ac = getActionClass(t.action || 'WAIT');

    if (lastSignal !== null && lastSignal !== s.signal) {
        const emoji = getSignalEmoji(s.signal);
        sendNotification(`🔄 Signal: ${s.signal}`, `${emoji} ${s.signal} (${s.confidence}%) — ${s.reason}`);
    }
    lastSignal = s.signal;

    const changedBadge = changed ? `<span class="signal-changed-badge">CHANGED</span>` : '';
    const actionBadge = `<div class="action-badge ${ac}">${t.action || 'WAIT'}</div>`;

    // RSI coloring
    let rsiClass = 'rsi';
    if (s.rsi > 70) rsiClass = 'rsi overbought';
    else if (s.rsi < 30) rsiClass = 'rsi oversold';

    // Trade card
    let tradeHtml = '';
    if (t.action && t.action !== 'WAIT' && t.action !== '') {
        tradeHtml = `<div class="trade-card"><h3>📊 ${t.action} — Suggested Trade</h3>
        <div class="trade-row"><span class="label">Entry</span><span class="value ${ac}">$${formatPrice(t.entry)}</span></div>
        <div class="trade-row"><span class="label">Stop Loss</span><span class="value" style="color:#ef4444">$${formatPrice(t.stop_loss)}</span></div>
        <div class="trade-row"><span class="label">Take Profit 1</span><span class="value" style="color:#10b981">$${formatPrice(t.take_profit_1)}</span></div>
        <div class="trade-row"><span class="label">Take Profit 2</span><span class="value" style="color:#10b981">$${formatPrice(t.take_profit_2)}</span></div>
        <div class="trade-row"><span class="label">Risk:Reward</span><span class="value">${t.risk_reward}</span></div>
        <div class="trade-row"><span class="label">Lots</span><span class="value">${t.lots}</span></div>
        <div class="trade-row"><span class="label">Margin</span><span class="value">${t.margin_needed}</span></div></div>`;
    } else {
        tradeHtml = `<div class="trade-card"><h3>⏸️ WAIT — No Trade</h3>
        <div style="text-align:center;font-size:12px;color:#9ca3af;padding:6px 0;">${t.message || 'Wait for a clear intraday signal.'}</div></div>`;
    }

    const hh = h.slice().reverse().map(h => {
        const c = h.changed ? `<span class="history-changed">⬆</span>` : '';
        return `<div class="history-item">
            <span class="history-time">${h.timestamp}</span>
            <span class="history-signal ${getSignalClass(h.signal)}">${getSignalEmoji(h.signal)} ${h.signal}${c}</span>
            <span class="history-price">$${formatPrice(h.price)}</span>
            <span class="history-conf">${h.confidence}%</span>
        </div>`;
    }).join('');

    document.getElementById('app').innerHTML = `
        <div class="price-card">
            <div class="price-label">XAU/USD — Intraday</div>
            <div class="price-value ${pc}">$${formatPrice(p.current)}</div>
            <div class="price-change ${pc}">${cs}$${formatPrice(p.change)}</div>
            <div class="price-details">
                <div><div class="label">5-Period High</div><div class="value">$${formatPrice(p.high)}</div></div>
                <div><div class="label">5-Period Low</div><div class="value">$${formatPrice(p.low)}</div></div>
                <div><div class="label">Data</div><div class="value">${d.data_points}</div></div>
            </div>
        </div>
        <div class="signal-card">
            <div class="signal-label">Intraday Signal ${changedBadge}</div>
            <div class="signal-icon">${getSignalEmoji(s.signal)}</div>
            <div class="signal-value ${sc}">${s.signal}</div>
            ${actionBadge}
            <div class="signal-confidence">Confidence: ${s.confidence}%</div>
            <div class="signal-reason">${s.reason}</div>
        </div>
        <div class="indicator-grid">
            <div class="indicator-card"><div class="ind-label">EMA 9</div><div class="ind-value ema-fast">$${formatPrice(s.ema9)}</div></div>
            <div class="indicator-card"><div class="ind-label">EMA 21</div><div class="ind-value ema-slow">$${formatPrice(s.ema21)}</div></div>
            <div class="indicator-card"><div class="ind-label">SMA 50</div><div class="ind-value sma">$${formatPrice(s.sma50)}</div></div>
            <div class="indicator-card"><div class="ind-label">RSI 14</div><div class="ind-value ${rsiClass}">${s.rsi}</div></div>
            <div class="indicator-card"><div class="ind-label">Momentum</div><div class="ind-value" style="color:${s.momentum > 0 ? '#10b981' : '#ef4444'}">${s.momentum > 0 ? '+' : ''}${s.momentum}</div></div>
            <div class="indicator-card"><div class="ind-label">BB Upper</div><div class="ind-value" style="color:#818cf8">$${formatPrice(s.bb_upper)}</div></div>
        </div>
        ${tradeHtml}
        <div class="history-card">
            <h3>📋 Intraday Signal History ${changed ? '<span style="color:#ef4444;font-size:10px;">— NEW!</span>' : ''}</h3>
            ${hh || '<div style="text-align:center;color:#6b7280;padding:10px;">No signals yet</div>'}
        </div>`;
}

async function fetchSignal() {
    try {
        const r = await fetch(API_BASE + '/signal');
        const d = await r.json();
        render(d);
        nextUpdateTime = Date.now() + 300000;
        if (countdownInterval) clearInterval(countdownInterval);
        countdownInterval = setInterval(updateCountdown, 1000);
        updateCountdown();
    } catch(e) {
        document.getElementById('app').innerHTML = `<div class="signal-card"><div style="text-align:center;padding:20px;color:#ef4444;">⚠️ Connection error. Retrying in 30s...</div></div>`;
    }
}

fetchSignal();
setInterval(fetchSignal, 300000);
</script>
</body>
</html>
