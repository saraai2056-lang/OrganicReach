import { useState, useEffect } from "react";

const G = "#00FF8C";
const SARA_FB = "https://www.facebook.com/saraai2056";

const TIPS = {
  posting: [
    { t: "Post at peak hours", d: "🇬🇧 UK: 7–9am, 12–2pm, 7–9pm GMT · 🇺🇸 USA: 9–11am, 1–3pm EST · 🇵🇰 Pakistan: 8–10am, 8–10pm PKT · 🇮🇳 India: 8–10am, 7–9pm IST. Posting at these times can boost reach by 40–60%." },
    { t: "Post 4–5x per week", d: "Consistency always beats volume. Four quality posts a week outperform fourteen rushed ones. Every algorithm rewards a regular, predictable posting schedule." },
    { t: "Story first, then main post", d: "Post a Story 30 minutes before your main feed post. This warms up the algorithm and stacks early engagement, pushing your post to more people organically." },
    { t: "Never delete and repost", d: "Deleting a post resets all its engagement data. Facebook and Instagram penalise this pattern. Always edit instead of deleting — even a low-performing post." },
  ],
  engagement: [
    { t: "Ask a question in every post", d: "Posts with a question in the caption get 2–3× more comments. End every caption simply: 'What do you think?' or 'Drop a 🔥 if you agree.' Comments signal value to the algorithm." },
    { t: "Reply within the first hour", d: "Replying to every comment in the first 60 minutes can double your organic reach. Facebook and Instagram heavily prioritise posts with fast, active comment threads." },
    { t: "Use polls and 'This or That' posts", d: "Interactive content (polls, quizzes, pick-one posts) gets 4× more shares than static posts. Run one poll on Stories every week — it trains your audience to engage regularly." },
    { t: "Comment on 5 niche pages daily", d: "Leave genuine, helpful comments on 5–10 posts in your niche every day. Their audience sees your comment and visits your page. This is free, targeted traffic most creators ignore." },
  ],
  algorithm: [
    { t: "Video beats images every time", d: "Short videos (Reels, TikToks, Shorts) get 3–5× more organic reach than images. Even a basic 30-second phone video filmed in natural light outperforms a professional graphic." },
    { t: "DM your post to warm contacts first", d: "Right after posting, send it to 5–10 engaged followers via DM. Early shares tell the algorithm your content is worth pushing to a wider audience. Most underused free tactic." },
    { t: "Use 3–5 targeted hashtags", d: "On Facebook, 3–5 specific hashtags outperform 30 generic ones. On Instagram, 8–12 is optimal. Choose hashtags where your exact audience is active — niche beats mega-popular." },
    { t: "Never buy followers", d: "Bought followers destroy your engagement rate. 1,000 real followers at 5% engagement is worth far more than 100,000 ghost accounts at 0.1%. Low engagement also suppresses reach for real followers." },
  ],
  growth: [
    { t: "Collaborate with similar-sized pages", d: "Find 3–5 pages in your niche with a similar following and do a weekly shoutout exchange. Both pages reach a new, relevant audience with zero cost and real followers gained." },
    { t: "Give away a free resource", d: "A free PDF guide, checklist, or template makes people follow and share your page. Ask them to 'Follow + Comment to receive' — this maximises both reach and new followers." },
    { t: "Pin your most engaging post", d: "Pin your single best-performing post to the top of your profile. New visitors see your most compelling content first — this alone can increase follow rate by 15–25%." },
    { t: "Cross-promote across all platforms", d: "Post your content on Facebook, Instagram, TikTok, and YouTube Shorts. Each platform algorithm is independent, so the same content gets fresh reach everywhere you post it." },
  ],
};

const SCHEDULES = {
  Facebook: {
    UK: "📅 Best days: Wednesday, Thursday, Friday\n⏰ Best times: 7–9am · 12–2pm · 7–9pm (GMT)\n📊 Frequency: 4–5 posts per week\n💡 Tip: Facebook videos under 3 minutes get the highest reach in the UK. Always add captions.",
    USA: "📅 Best days: Wednesday, Thursday, Friday\n⏰ Best times: 9–11am · 1–3pm · 7–9pm (EST)\n📊 Frequency: 4–5 posts per week\n💡 Tip: Thursday 1–4pm EST is statistically the peak engagement window for US Facebook pages.",
    Pakistan: "📅 Best days: Monday, Wednesday, Friday, Sunday\n⏰ Best times: 8–10am · 1–3pm · 8–10pm (PKT)\n📊 Frequency: 5–6 posts per week\n💡 Tip: Friday afternoon after Juma prayer is the highest-traffic time for Pakistani Facebook audience.",
    India: "📅 Best days: Tuesday, Wednesday, Thursday, Saturday\n⏰ Best times: 8–10am · 1–2pm · 7–9pm (IST)\n📊 Frequency: 5 posts per week\n💡 Tip: Sunday evenings 7–9pm IST are peak for entertainment and lifestyle content in India.",
  },
  Instagram: {
    UK: "📅 Best days: Monday, Tuesday, Thursday\n⏰ Best times: 6–8am · 12–1pm · 7–9pm (GMT)\n📊 Frequency: 4–5 posts/week + daily Stories\n💡 Tip: Reels posted before 9am in the UK get 60% more reach than afternoon posts.",
    USA: "📅 Best days: Monday, Wednesday, Friday\n⏰ Best times: 6–9am · 12–2pm (EST)\n📊 Frequency: 4–5 posts/week + daily Stories\n💡 Tip: Wednesday 11am–1pm EST is peak Instagram engagement for US audiences across most niches.",
    Pakistan: "📅 Best days: Monday, Wednesday, Friday, Saturday\n⏰ Best times: 9–11am · 8–10pm (PKT)\n📊 Frequency: 5–6 posts/week + daily Stories\n💡 Tip: Evening Reels at 8–10pm PKT consistently dominate Instagram reach for Pakistani creators.",
    India: "📅 Best days: Wednesday, Thursday, Friday, Sunday\n⏰ Best times: 9–11am · 7–9pm (IST)\n📊 Frequency: 5 posts/week + daily Stories\n💡 Tip: Sunday Reels in India get the highest saves and shares, especially in food and entertainment.",
  },
  TikTok: {
    UK: "📅 Best days: Tuesday, Thursday, Friday\n⏰ Best times: 7–9am · 12–3pm · 7–9pm (GMT)\n📊 Frequency: 1–3 videos per day\n💡 Tip: Hook viewers in the first 2 seconds — TikTok measures watch time from frame 1. Start mid-action.",
    USA: "📅 Best days: Tuesday, Thursday, Friday\n⏰ Best times: 6–8am · 10am–12pm · 7–9pm (EST)\n📊 Frequency: 1–3 videos per day\n💡 Tip: Thursday 7pm EST consistently outperforms all other US TikTok posting slots across categories.",
    Pakistan: "📅 Best days: Monday–Friday, Saturday evening\n⏰ Best times: 8–10am · 9–11pm (PKT)\n📊 Frequency: 2–3 videos per day\n💡 Tip: Night-time TikTok (9–11pm PKT) dominates engagement for the Pakistani audience.",
    India: "📅 Best days: Monday, Wednesday, Friday, Saturday, Sunday\n⏰ Best times: 7–9am · 7–10pm (IST)\n📊 Frequency: 2–3 videos per day\n💡 Tip: Dance, comedy, and everyday life content consistently trends in Indian Reels and TikTok.",
  },
  YouTube: {
    UK: "📅 Best days: Thursday, Friday, Saturday\n⏰ Best times: 2–4pm · 6–8pm (GMT)\n📊 Frequency: 1–2 videos per week\n💡 Tip: YouTube Shorts posted on Thursday or Friday get the highest first-48-hour UK view counts.",
    USA: "📅 Best days: Friday, Saturday, Sunday\n⏰ Best times: 2–4pm · 5–8pm (EST)\n📊 Frequency: 1–2 videos per week\n💡 Tip: Friday 3–5pm EST is peak click-through time for YouTube in the US across most categories.",
    Pakistan: "📅 Best days: Friday, Saturday, Sunday\n⏰ Best times: 6–8pm · 9–11pm (PKT)\n📊 Frequency: 1–2 videos per week\n💡 Tip: Weekend evenings dominate YouTube in Pakistan. Educational and comedy content leads all categories.",
    India: "📅 Best days: Saturday, Sunday (Thursday also strong)\n⏰ Best times: 7–9pm (IST)\n📊 Frequency: 1–2 videos per week\n💡 Tip: Hindi and regional language content gets 3× more organic reach in Indian YouTube. Add subtitles.",
  },
};

const TASKS = [
  "Post today's content at the right peak time for your region",
  "Reply to all comments within 1 hour of posting",
  "Leave genuine comments on 5 posts in your niche",
  "Post 1 Story or short video today",
  "Check your page insights and note what performed best",
  "Follow or connect with 3 relevant accounts in your niche",
  "Share your post to a relevant group or community",
  "Plan tomorrow's content before you sleep",
];

const css = `
  @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=DM+Sans:wght@400;600;700&display=swap');
  * { box-sizing: border-box; margin: 0; padding: 0; }
  :root {
    --g: #00FF8C; --g2: #00C96B; --bg: #030C06; --card: #071209;
    --border: rgba(0,255,140,0.15); --b2: rgba(0,255,140,0.08);
    --text: #d0eedd; --muted: #4a7a5a; --dim: #2a4a35;
  }
  body { background: var(--bg); font-family: 'DM Sans', sans-serif; color: var(--text); }
  .page { max-width: 460px; margin: 0 auto; padding: 16px 14px 60px; position: relative; }
  .page::before {
    content: ''; position: fixed; inset: 0;
    background-image: linear-gradient(rgba(0,255,140,0.03) 1px,transparent 1px),
      linear-gradient(90deg,rgba(0,255,140,0.03) 1px,transparent 1px);
    background-size: 36px 36px; z-index: -1; pointer-events: none;
  }
  .topnav { display:flex; align-items:center; justify-content:space-between; padding:10px 0 18px; }
  .logo { font-family:'Bebas Neue',sans-serif; font-size:28px; color:#fff; letter-spacing:2px; }
  .logo em { color:var(--g); font-style:normal; }
  .live { display:flex; align-items:center; gap:6px; font-size:10px; font-weight:700;
    color:var(--g); background:rgba(0,255,140,0.08); border:1px solid var(--border);
    padding:5px 10px; border-radius:20px; letter-spacing:1px; }
  .dot { width:7px; height:7px; background:var(--g); border-radius:50%; animation:pulse 2s infinite; }
  @keyframes pulse { 0%,100%{box-shadow:0 0 0 0 rgba(0,255,140,0.5)} 50%{box-shadow:0 0 0 5px rgba(0,255,140,0)} }
  .hero { text-align:center; padding:8px 0 20px; }
  .hero-tag { font-size:10px; letter-spacing:3px; text-transform:uppercase; color:var(--muted); margin-bottom:8px; }
  .hero h1 { font-family:'Bebas Neue',sans-serif; font-size:48px; line-height:1; color:#fff; letter-spacing:2px; }
  .hero h1 em { color:var(--g); font-style:normal; text-shadow:0 0 40px rgba(0,255,140,0.3); }
  .hero-sub { font-size:13px; color:var(--muted); margin-top:8px; line-height:1.6; }
  .fb-btn { display:flex; align-items:center; justify-content:center; gap:8px;
    background:linear-gradient(135deg,#1877F2,#0d5fd4); color:#fff; border:none;
    border-radius:14px; padding:14px 20px; font-family:'DM Sans',sans-serif;
    font-weight:700; font-size:14px; cursor:pointer; width:100%; margin:16px 0 20px;
    box-shadow:0 6px 24px rgba(24,119,242,0.3); transition:transform 0.15s; }
  .fb-btn:hover { transform:scale(1.01); }
  .fb-btn:active { transform:scale(0.97); }
  .regions { display:flex; flex-wrap:wrap; gap:6px; justify-content:center; margin-bottom:20px; }
  .rtag { font-size:11px; font-weight:600; padding:5px 12px; border-radius:20px;
    border:1px solid var(--b2); background:rgba(0,255,140,0.04); color:#7acb97; }
  .sec { font-size:10px; letter-spacing:3px; text-transform:uppercase; color:var(--muted);
    margin:26px 0 12px; display:flex; align-items:center; gap:8px; }
  .sec::after { content:''; flex:1; height:1px; background:var(--b2); }
  .tcard { background:var(--card); border:1px solid var(--b2); border-radius:20px; padding:18px; margin-bottom:12px; }
  .thead { display:flex; align-items:center; gap:10px; margin-bottom:14px; }
  .ticon { width:40px; height:40px; border-radius:12px; background:rgba(0,255,140,0.08);
    border:1px solid var(--border); display:flex; align-items:center; justify-content:center;
    font-size:20px; flex-shrink:0; }
  .ttitle { font-weight:700; font-size:14px; color:#fff; }
  .tdesc { font-size:11px; color:var(--muted); margin-top:2px; line-height:1.4; }
  .row { display:flex; gap:8px; margin-bottom:10px; }
  .inp { flex:1; background:rgba(0,0,0,0.35); border:1px solid var(--b2); border-radius:12px;
    padding:11px 13px; font-family:'DM Sans',sans-serif; font-size:13px; color:var(--text);
    outline:none; transition:border-color 0.2s; min-width:0; }
  .inp:focus { border-color:rgba(0,255,140,0.4); }
  .inp::placeholder { color:var(--dim); }
  select.inp { cursor:pointer; }
  .run { background:linear-gradient(135deg,var(--g),var(--g2)); color:#030C06;
    border:none; border-radius:12px; padding:11px 16px; font-family:'DM Sans',sans-serif;
    font-weight:700; font-size:13px; cursor:pointer; white-space:nowrap; flex-shrink:0;
    transition:opacity 0.2s,transform 0.15s; }
  .run:active { transform:scale(0.96); }
  .run:disabled { opacity:0.45; cursor:not-allowed; }
  .out { background:rgba(0,0,0,0.25); border:1px solid var(--b2); border-radius:14px;
    padding:14px 14px 14px 14px; font-size:12px; line-height:1.8; color:#b0d8c0;
    white-space:pre-wrap; word-break:break-word; position:relative; }
  .cp { position:absolute; top:8px; right:8px; background:rgba(0,255,140,0.1);
    border:1px solid var(--border); color:var(--g); border-radius:8px; padding:4px 9px;
    font-size:10px; font-weight:700; cursor:pointer; }
  .loading { display:flex; align-items:center; gap:8px; color:var(--muted); font-size:12px; }
  .dots span { width:6px; height:6px; background:var(--g); border-radius:50%;
    display:inline-block; animation:blink 1.2s infinite; margin:0 1px; }
  .dots span:nth-child(2){animation-delay:.2s} .dots span:nth-child(3){animation-delay:.4s}
  @keyframes blink{0%,100%{opacity:.2;transform:translateY(0)}50%{opacity:1;transform:translateY(-3px)}}
  .tips-grid { display:grid; grid-template-columns:1fr 1fr; gap:10px; margin-bottom:12px; }
  .tip-box { background:var(--card); border:1px solid var(--b2); border-radius:16px;
    padding:14px; cursor:pointer; transition:all 0.2s; }
  .tip-box.on { border-color:rgba(0,255,140,0.4); background:rgba(0,255,140,0.04); }
  .tip-icon { font-size:22px; margin-bottom:6px; }
  .tip-title { font-size:12px; font-weight:700; color:#fff; }
  .tip-sub { font-size:10px; color:var(--muted); margin-top:2px; }
  .tips-panel { background:var(--card); border:1px solid var(--border); border-radius:16px; padding:16px; }
  .titem { display:flex; gap:10px; padding:10px 0; border-bottom:1px solid var(--b2); }
  .titem:last-child { border-bottom:none; padding-bottom:0; }
  .tnum { font-family:'Bebas Neue',sans-serif; font-size:22px; color:var(--g); line-height:1; flex-shrink:0; width:26px; }
  .ttext { font-size:12px; line-height:1.65; color:var(--text); }
  .ttext strong { color:var(--g); font-weight:700; }
  .sch-card { background:var(--card); border:1px solid var(--b2); border-radius:20px; padding:18px; margin-bottom:12px; }
  .sch-grid { display:grid; grid-template-columns:1fr 1fr; gap:8px; margin-bottom:12px; }
  .sch-lbl { font-size:10px; color:var(--muted); letter-spacing:1px; text-transform:uppercase; margin-bottom:5px; }
  .cl-card { background:var(--card); border:1px solid var(--b2); border-radius:20px; padding:18px; margin-bottom:12px; }
  .ci { display:flex; align-items:flex-start; gap:10px; padding:8px 0; border-bottom:1px solid var(--b2); cursor:pointer; }
  .ci:last-child { border-bottom:none; padding-bottom:0; }
  .chk { width:19px; height:19px; border:2px solid var(--b2); border-radius:5px; flex-shrink:0;
    margin-top:1px; display:flex; align-items:center; justify-content:center; transition:all 0.2s; }
  .chk.on { background:var(--g); border-color:var(--g); }
  .ct { font-size:12px; line-height:1.55; color:var(--text); }
  .ct.done { text-decoration:line-through; color:var(--muted); }
  .meter { height:6px; background:rgba(0,255,140,0.08); border-radius:10px; margin-top:12px; overflow:hidden; }
  .mfill { height:100%; background:linear-gradient(90deg,var(--g2),var(--g)); border-radius:10px; transition:width 0.4s; }
  .mlbl { font-size:10px; color:var(--muted); margin-top:6px; text-align:right; }
  .footer { text-align:center; margin-top:36px; padding-top:18px; border-top:1px solid var(--b2); }
  .footer p { font-size:11px; color:var(--muted); line-height:1.8; }
  .footer strong { color:var(--g); }
  .team { display:flex; justify-content:center; gap:8px; margin-top:12px; }
  .agent { font-size:10px; font-weight:700; letter-spacing:2px; text-transform:uppercase; color:var(--g);
    background:rgba(0,255,140,0.06); border:1px solid var(--border); padding:4px 12px; border-radius:20px; }
  .toast { position:fixed; bottom:20px; left:50%; transform:translateX(-50%) translateY(80px);
    background:rgba(0,255,140,0.12); border:1px solid rgba(0,255,140,0.3); color:var(--g);
    padding:10px 20px; border-radius:30px; font-size:12px; font-weight:600; z-index:999;
    transition:transform 0.3s; pointer-events:none; }
  .toast.on { transform:translateX(-50%) translateY(0); }
`;

function Loader() {
  return (
    <div className="loading">
      <div className="dots">
        <span/><span/><span/>
      </div>
      AI is writing...
    </div>
  );
}

function Output({ text, id, onCopy }) {
  if (!text) return null;
  if (text === "loading") return <div className="out"><Loader /></div>;
  return (
    <div className="out" id={id}>
      <button className="cp" onClick={() => onCopy(text)}>Copy</button>
      {text}
    </div>
  );
}

async function callAI(prompt) {
  const res = await fetch("https://api.anthropic.com/v1/messages", {
    method: "POST",
    headers: { "Content-Type": "application/json" },
    body: JSON.stringify({
      model: "claude-sonnet-4-20250514",
      max_tokens: 1000,
      messages: [{ role: "user", content: prompt }],
    }),
  });
  const data = await res.json();
  return data.content?.find(b => b.type === "text")?.text || "No response. Please try again.";
}

export default function App() {
  const [toast, setToast] = useState(false);
  const [tipKey, setTipKey] = useState("posting");
  const [schP, setSchP] = useState("Facebook");
  const [schR, setSchR] = useState("UK");
  const [checks, setChecks] = useState(Array(TASKS.length).fill(false));

  // Tool states
  const [hashNiche, setHashNiche] = useState("");
  const [hashP, setHashP] = useState("Facebook");
  const [hashR, setHashR] = useState("UK");
  const [hashOut, setHashOut] = useState("");

  const [ideaNiche, setIdeaNiche] = useState("");
  const [ideaR, setIdeaR] = useState("UK");
  const [ideaOut, setIdeaOut] = useState("");

  const [capTopic, setCapTopic] = useState("");
  const [capTone, setCapTone] = useState("Engaging and conversational");
  const [capP, setCapP] = useState("Facebook");
  const [capOut, setCapOut] = useState("");

  const [bioText, setBioText] = useState("");
  const [bioP, setBioP] = useState("Facebook");
  const [bioOut, setBioOut] = useState("");

  const copyText = (text) => {
    navigator.clipboard.writeText(text).then(() => {
      setToast(true);
      setTimeout(() => setToast(false), 2200);
    });
  };

  const toggle = (i) => {
    const c = [...checks];
    c[i] = !c[i];
    setChecks(c);
  };
  const done = checks.filter(Boolean).length;
  const pct = Math.round(done / TASKS.length * 100);

  const run = async (tool) => {
    const setters = { hashtag: setHashOut, ideas: setIdeaOut, caption: setCapOut, bio: setBioOut };
    const set = setters[tool];
    const prompts = {
      hashtag: hashNiche ? `You are a social media growth expert.\n\nPlatform: ${hashP}\nNiche: ${hashNiche}\nRegion: ${hashR}\n\nGenerate the best hashtags for maximum organic reach. Provide:\n1. 5 HIGH-REACH hashtags (millions of posts — broad awareness)\n2. 5 MID-RANGE hashtags (100k–1M posts — targeted audience)\n3. 5 NICHE hashtags (under 100k posts — highly engaged)\n4. One specific tip for using hashtags on ${hashP} in ${hashR}\n\nBe specific to the niche and region. Format clearly with numbered sections.` : null,
      ideas: ideaNiche ? `You are a content strategist specialising in organic social media growth.\n\nPage niche: ${ideaNiche}\nTarget region: ${ideaR}\n\nCreate a practical 7-day content calendar. For each day:\n- Day number and post type (Reel, image, poll, Story, etc.)\n- Specific post idea — actionable and detailed\n- One line: why it will perform well with the ${ideaR} audience\n\nBe culturally relevant to ${ideaR}. Keep each day concise but genuinely useful.` : null,
      caption: capTopic ? `Write a ${capTone} caption for ${capP}.\n\nPost topic: ${capTopic}\n\nRequirements:\n- Strong hook in the first line that stops the scroll\n- 3–5 sentences of genuine value or emotion\n- End with a question or call-to-action to drive comments\n- 3–5 natural emojis placed well\n- Sound human and authentic, not robotic or corporate\n\nWrite one complete, ready-to-post caption. No explanations.` : null,
      bio: bioText ? `Write an optimised ${bioP} profile bio.\n\nPage: ${bioText}\n\nRequirements:\n- Under 150 characters\n- Clearly states the value the page gives visitors\n- 1–2 relevant emojis\n- Ends with a soft call-to-action (Follow for... / Join us...)\n- Sounds human and genuine\n\nWrite 2 versions: one professional, one more casual and friendly. Label them clearly.` : null,
    };
    const prompt = prompts[tool];
    if (!prompt) { alert("Please fill in the field above first."); return; }
    set("loading");
    try {
      const result = await callAI(prompt);
      set(result);
    } catch (e) {
      set("Connection error. Please try again.");
    }
  };

  const scheduleText = SCHEDULES[schP]?.[schR] || "";

  return (
    <>
      <style>{css}</style>
      <div className={`toast${toast ? " on" : ""}`}>✓ Copied to clipboard!</div>
      <div className="page">

        {/* NAV */}
        <div className="topnav">
          <div className="logo">Sara<em>AI</em></div>
          <div className="live"><span className="dot" />TOOLS LIVE</div>
        </div>

        {/* HERO */}
        <div className="hero">
          <div className="hero-tag">Free Organic Growth Toolkit</div>
          <h1>Grow <em>Real</em><br />Followers</h1>
          <p className="hero-sub">100% organic AI tools. No fake followers. No bots.<br />Real, lasting growth for your page.</p>
        </div>

        {/* FOLLOW BUTTON */}
        <button className="fb-btn" onClick={() => window.open(SARA_FB, "_blank")}>
          <svg width="20" height="20" viewBox="0 0 24 24" fill="white"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
          Follow Sara AI on Facebook
        </button>

        {/* REGIONS */}
        <div className="regions">
          <span className="rtag">🇬🇧 UK</span>
          <span className="rtag">🇺🇸 USA</span>
          <span className="rtag">🇵🇰 Pakistan</span>
          <span className="rtag">🇮🇳 India</span>
          <span className="rtag">🌍 Global</span>
        </div>

        {/* TOOL 1 — HASHTAGS */}
        <div className="sec">AI Hashtag Generator</div>
        <div className="tcard">
          <div className="thead">
            <div className="ticon">🏷️</div>
            <div><div className="ttitle">Viral Hashtag Builder</div>
              <div className="tdesc">Get real targeted hashtags for your niche and platform</div></div>
          </div>
          <div className="row">
            <input className="inp" value={hashNiche} onChange={e => setHashNiche(e.target.value)} placeholder="Your niche (e.g. food, fitness, tech...)" />
          </div>
          <div className="row">
            <select className="inp" value={hashP} onChange={e => setHashP(e.target.value)}>
              <option>Facebook</option><option>Instagram</option><option>TikTok</option><option>YouTube</option>
            </select>
            <select className="inp" value={hashR} onChange={e => setHashR(e.target.value)}>
              <option>UK</option><option>USA</option><option>Pakistan</option><option>India</option><option>Global</option>
            </select>
            <button className="run" onClick={() => run("hashtag")} disabled={hashOut === "loading"}>Run</button>
          </div>
          <Output text={hashOut} onCopy={copyText} />
        </div>

        {/* TOOL 2 — IDEAS */}
        <div className="sec">AI Content Ideas</div>
        <div className="tcard">
          <div className="thead">
            <div className="ticon">💡</div>
            <div><div className="ttitle">7-Day Content Calendar</div>
              <div className="tdesc">Posts your audience actually wants — planned for a full week</div></div>
          </div>
          <div className="row">
            <input className="inp" value={ideaNiche} onChange={e => setIdeaNiche(e.target.value)} placeholder="What is your page about?" />
            <select className="inp" style={{ maxWidth: 120 }} value={ideaR} onChange={e => setIdeaR(e.target.value)}>
              <option>UK</option><option>USA</option><option>Pakistan</option><option>India</option><option>Global</option>
            </select>
          </div>
          <div className="row">
            <button className="run" style={{ width: "100%" }} onClick={() => run("ideas")} disabled={ideaOut === "loading"}>Generate 7-Day Plan</button>
          </div>
          <Output text={ideaOut} onCopy={copyText} />
        </div>

        {/* TOOL 3 — CAPTION */}
        <div className="sec">AI Caption Writer</div>
        <div className="tcard">
          <div className="thead">
            <div className="ticon">✍️</div>
            <div><div className="ttitle">Caption Generator</div>
              <div className="tdesc">Scroll-stopping captions that drive comments, shares and follows</div></div>
          </div>
          <div className="row">
            <input className="inp" value={capTopic} onChange={e => setCapTopic(e.target.value)} placeholder="Describe your post (e.g. sunset photo, new product...)" />
          </div>
          <div className="row">
            <select className="inp" value={capTone} onChange={e => setCapTone(e.target.value)}>
              <option value="Engaging and conversational">Engaging</option>
              <option value="Funny and witty">Funny</option>
              <option value="Inspirational">Inspiring</option>
              <option value="Professional">Professional</option>
              <option value="Emotional and personal">Emotional</option>
            </select>
            <select className="inp" value={capP} onChange={e => setCapP(e.target.value)}>
              <option>Facebook</option><option>Instagram</option><option>TikTok</option>
            </select>
            <button className="run" onClick={() => run("caption")} disabled={capOut === "loading"}>Write</button>
          </div>
          <Output text={capOut} onCopy={copyText} />
        </div>

        {/* TOOL 4 — BIO */}
        <div className="sec">AI Bio Optimizer</div>
        <div className="tcard">
          <div className="thead">
            <div className="ticon">👤</div>
            <div><div className="ttitle">Profile Bio Writer</div>
              <div className="tdesc">A strong bio converts visitors into followers — let AI write yours</div></div>
          </div>
          <div className="row">
            <input className="inp" value={bioText} onChange={e => setBioText(e.target.value)} placeholder="Tell us about your page in a few words..." />
          </div>
          <div className="row">
            <select className="inp" value={bioP} onChange={e => setBioP(e.target.value)}>
              <option>Facebook</option><option>Instagram</option><option>TikTok</option><option>YouTube</option>
            </select>
            <button className="run" onClick={() => run("bio")} disabled={bioOut === "loading"}>Optimize</button>
          </div>
          <Output text={bioOut} onCopy={copyText} />
        </div>

        {/* TIPS */}
        <div className="sec">Organic Growth Tips</div>
        <div className="tips-grid">
          {[
            { k: "posting", icon: "📅", t: "Posting Times", s: "When to post by region" },
            { k: "engagement", icon: "💬", t: "Engagement", s: "Get more comments & shares" },
            { k: "algorithm", icon: "📈", t: "Algorithm", s: "How to beat the feed" },
            { k: "growth", icon: "🚀", t: "Fast Growth", s: "Proven organic tactics" },
          ].map(item => (
            <div key={item.k} className={`tip-box${tipKey === item.k ? " on" : ""}`} onClick={() => setTipKey(item.k)}>
              <div className="tip-icon">{item.icon}</div>
              <div className="tip-title">{item.t}</div>
              <div className="tip-sub">{item.s}</div>
            </div>
          ))}
        </div>
        <div className="tips-panel">
          {TIPS[tipKey].map((item, i) => (
            <div key={i} className="titem">
              <div className="tnum">0{i + 1}</div>
              <div className="ttext"><strong>{item.t}</strong><br />{item.d}</div>
            </div>
          ))}
        </div>

        {/* SCHEDULE */}
        <div className="sec">Best Posting Schedule</div>
        <div className="sch-card">
          <div className="sch-grid">
            <div>
              <div className="sch-lbl">Platform</div>
              <select className="inp" value={schP} onChange={e => setSchP(e.target.value)}>
                <option>Facebook</option><option>Instagram</option><option>TikTok</option><option>YouTube</option>
              </select>
            </div>
            <div>
              <div className="sch-lbl">Region</div>
              <select className="inp" value={schR} onChange={e => setSchR(e.target.value)}>
                <option>UK</option><option>USA</option><option>Pakistan</option><option>India</option>
              </select>
            </div>
          </div>
          <div className="out" style={{ fontSize: 12 }}>{scheduleText}</div>
        </div>

        {/* CHECKLIST */}
        <div className="sec">Daily Growth Checklist</div>
        <div className="cl-card">
          {TASKS.map((task, i) => (
            <div key={i} className="ci" onClick={() => toggle(i)}>
              <div className={`chk${checks[i] ? " on" : ""}`}>
                {checks[i] && <span style={{ fontSize: 11, color: "#030C06", fontWeight: 900 }}>✓</span>}
              </div>
              <div className={`ct${checks[i] ? " done" : ""}`}>{task}</div>
            </div>
          ))}
        </div>
        <div className="meter"><div className="mfill" style={{ width: pct + "%" }} /></div>
        <div className="mlbl">{done} / {TASKS.length} tasks complete — {pct}%</div>

        {/* FOOTER */}
        <div className="footer">
          <p>
            Built by <strong>Sara AI</strong> to help creators grow honestly.<br />
            No fake followers. No paid ads. Just <strong>real organic growth</strong>.<br />
            Optimised for 🇬🇧 UK · 🇺🇸 USA · 🇵🇰 Pakistan · 🇮🇳 India
          </p>
          <button className="fb-btn" style={{ marginTop: 14, fontSize: 13 }} onClick={() => window.open(SARA_FB, "_blank")}>
            <svg width="18" height="18" viewBox="0 0 24 24" fill="white"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
            Join Sara AI Community on Facebook
          </button>
          <div className="team" style={{ marginTop: 14 }}>
            <span className="agent">Atlas</span>
            <span className="agent">Nova</span>
            <span className="agent">Sage</span>
          </div>
        </div>

      </div>
    </>
  );
}
