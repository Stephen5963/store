<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Community Store — Campus Marketplace</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/tabler-icons.min.css">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --g:#1D9E75;--gd:#0F6E56;--gl:#E1F5EE;--glc:#085041;
  --amber:#EF9F27;--bl:#E6F1FB;--bc:#185FA5;
  --pl:#EEEDFE;--pc:#3C3489;--ol:#FAEEDA;--oc:#854F0B;
  --red:#E24B4A;--pink:#FBEAF0;--pinkc:#72243E;
  --txt:#111110;--muted:#6b6b67;--border:rgba(0,0,0,0.1);
  --bg:#fff;--bg2:#f5f5f2;--bg3:#e8e8e5;
  --rmd:10px;--rlg:16px;--rfull:999px;
  --shadow:0 2px 16px rgba(0,0,0,0.08);
}
@media(prefers-color-scheme:dark){
  :root{
    --txt:#f0f0ec;--muted:#9a9a96;--border:rgba(255,255,255,0.12);
    --bg:#1c1c1a;--bg2:#272725;--bg3:#323230;
    --gl:#08301f;--bl:#0c1f36;--pl:#17143a;--ol:#231908;--pink:#2a1020;
  }
}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif;background:var(--bg2);display:flex;flex-direction:column;align-items:center;padding:20px 12px 48px;min-height:100vh;color:var(--txt)}
.page-label{font-size:12px;color:var(--muted);margin-bottom:14px;text-align:center;letter-spacing:.4px}

/* ── PHONE SHELL ── */
.phone{width:390px;max-width:100%;min-height:780px;border:1.5px solid var(--border);border-radius:44px;overflow:hidden;background:var(--bg);display:flex;flex-direction:column;box-shadow:0 12px 48px rgba(0,0,0,0.14);position:relative}
@media(max-width:400px){
  body{padding:8px 0 32px}
  .phone{border-radius:0;border-left:none;border-right:none;min-height:100vh}
}

/* ── STATUS BAR ── */
.sbar{background:var(--g);color:#fff;font-size:11px;font-weight:600;padding:12px 22px 8px;display:flex;justify-content:space-between;align-items:center;flex-shrink:0}

/* ── SCREENS ── */
.screen{display:none;flex-direction:column;flex:1;min-height:0;overflow:hidden}
.screen.active{display:flex}
.scroll{flex:1;overflow-y:auto;-webkit-overflow-scrolling:touch}
.scroll::-webkit-scrollbar{display:none}

/* ── HEADERS ── */
.hdr{background:var(--g);padding:12px 16px 14px;flex-shrink:0}
.hdr-row{display:flex;align-items:center;gap:10px}
.hdr h2{font-size:19px;font-weight:700;color:#fff}
.hdr p{font-size:12px;color:rgba(255,255,255,.8);margin-top:2px}
.hdr-title{font-size:17px;font-weight:700;color:#fff;flex:1}
.back{background:rgba(255,255,255,.15);border:none;border-radius:50%;width:36px;height:36px;display:flex;align-items:center;justify-content:center;cursor:pointer;color:#fff;font-size:19px;flex-shrink:0;transition:background .15s,transform .1s}
.back:hover{background:rgba(255,255,255,.25)}.back:active{transform:scale(.92)}
.ibtn{background:rgba(255,255,255,.15);border:none;border-radius:50%;width:36px;height:36px;display:flex;align-items:center;justify-content:center;cursor:pointer;color:#fff;font-size:19px;transition:background .15s,transform .1s}
.ibtn:hover{background:rgba(255,255,255,.25)}.ibtn:active{transform:scale(.92)}

/* ── NAV ── */
.nav{background:var(--bg);border-top:.5px solid var(--border);display:flex;justify-content:space-around;padding:6px 0 16px;flex-shrink:0}
.nitem{display:flex;flex-direction:column;align-items:center;gap:2px;cursor:pointer;font-size:10px;color:var(--muted);background:none;border:none;padding:6px 10px;border-radius:12px;transition:color .15s,transform .1s;position:relative}
.nitem i{font-size:22px}.nitem.active{color:var(--g)}.nitem:active{transform:scale(.9)}
.sell-fab{background:var(--g);border-radius:50%;width:46px;height:46px;display:flex;align-items:center;justify-content:center;margin-top:-22px;border:3px solid var(--bg2);transition:background .15s,transform .1s}
.sell-fab:hover{background:var(--gd)}.sell-fab:active{transform:scale(.92)}
.sell-fab i{color:#fff;font-size:24px}

/* ── SEARCH BAR ── */
.searchbar{margin:12px 12px 8px;display:flex;align-items:center;background:var(--bg2);border:.5px solid var(--border);border-radius:var(--rfull);padding:10px 16px;gap:8px;cursor:text;transition:border-color .15s}
.searchbar:hover{border-color:var(--g)}
.searchbar i{color:var(--muted);font-size:17px;flex-shrink:0}
.searchbar input{border:none;background:transparent;font-size:14px;color:var(--txt);outline:none;flex:1;font-family:inherit}
.searchbar input::placeholder{color:var(--muted)}
.searchbar .clear-btn{background:none;border:none;cursor:pointer;color:var(--muted);font-size:17px;display:none;padding:0;line-height:1}
.searchbar input:not(:placeholder-shown) ~ .clear-btn{display:block}

/* ── CHIPS ── */
.chips{display:flex;gap:8px;padding:0 12px 6px;overflow-x:auto;scrollbar-width:none}
.chips::-webkit-scrollbar{display:none}
.chip{background:var(--bg2);border:.5px solid var(--border);border-radius:var(--rfull);padding:7px 16px;font-size:12px;white-space:nowrap;cursor:pointer;color:var(--muted);flex-shrink:0;transition:all .15s;font-family:inherit}
.chip:hover{background:var(--bg3)}.chip:active{transform:scale(.95)}.chip.active{background:var(--g);color:#fff;border-color:var(--g)}

/* ── BANNER ── */
.banner{margin:6px 12px 2px;background:var(--gd);border-radius:var(--rlg);padding:16px 60px 16px 16px;color:#fff;position:relative;overflow:hidden}
.banner::after{content:'🛍️';position:absolute;right:10px;top:50%;transform:translateY(-50%);font-size:44px;opacity:.28}
.banner h3{font-size:15px;font-weight:700}
.banner p{font-size:12px;opacity:.85;margin-top:3px}
.banner-btn{background:rgba(255,255,255,.2);border:1px solid rgba(255,255,255,.4);border-radius:var(--rfull);color:#fff;font-size:12px;font-weight:600;padding:6px 16px;margin-top:12px;cursor:pointer;transition:background .15s,transform .1s;display:inline-block;font-family:inherit}
.banner-btn:hover{background:rgba(255,255,255,.32)}.banner-btn:active{transform:scale(.96)}

/* ── SECTION TITLE ── */
.stitle{font-size:15px;font-weight:700;color:var(--txt);padding:10px 12px 6px;display:flex;justify-content:space-between;align-items:center}
.stitle a{font-size:12px;color:var(--g);font-weight:500;cursor:pointer;text-decoration:none}

/* ── PRODUCT GRID ── */
.pgrid{display:grid;grid-template-columns:1fr 1fr;gap:10px;padding:0 12px 14px}
.pcard{background:var(--bg);border:.5px solid var(--border);border-radius:var(--rlg);overflow:hidden;cursor:pointer;transition:transform .15s,box-shadow .15s}
.pcard:hover{transform:translateY(-2px);box-shadow:var(--shadow)}.pcard:active{transform:scale(.97)}
.pimg{height:90px;display:flex;align-items:center;justify-content:center;font-size:40px;position:relative}
.pinfo{padding:8px 10px 10px}
.pname{font-size:12px;font-weight:700;color:var(--txt);line-height:1.3}
.pprice{font-size:14px;color:var(--g);font-weight:700;margin-top:3px}
.pseller{font-size:11px;color:var(--muted);margin-top:1px}
.pstars{font-size:10px;color:var(--amber);margin-top:2px}
.pwish{position:absolute;top:6px;right:6px;background:rgba(255,255,255,.85);border:none;border-radius:50%;width:26px;height:26px;display:flex;align-items:center;justify-content:center;cursor:pointer;font-size:14px;color:var(--muted);transition:color .15s,transform .1s;backdrop-filter:blur(4px)}
.pwish:hover{color:var(--red)}.pwish:active{transform:scale(.9)}.pwish.active{color:var(--red)}

/* ── BUTTONS ── */
.btn{display:flex;align-items:center;justify-content:center;gap:8px;border:none;border-radius:var(--rfull);padding:14px;width:100%;font-size:15px;font-weight:600;cursor:pointer;transition:background .15s,transform .1s;font-family:inherit;margin-top:10px}
.btn:active{transform:scale(.98)}
.btn-g{background:var(--g);color:#fff}.btn-g:hover{background:var(--gd)}
.btn-s{background:var(--bg2);color:var(--txt);border:.5px solid var(--border)}.btn-s:hover{background:var(--bg3)}
.btn-r{background:#fef2f2;color:var(--red);border:.5px solid rgba(226,75,74,.2)}.btn-r:hover{background:#fee2e2}
.btn-sm{padding:9px 20px;width:auto;font-size:13px;margin-top:0}

/* ── DETAIL ── */
.dimg{height:220px;display:flex;align-items:center;justify-content:center;font-size:86px;flex-shrink:0;position:relative;overflow:hidden}
.dimg-uploaded{position:absolute;inset:0;object-fit:cover;width:100%;height:100%}
.dbody{padding:16px}
.dprice{font-size:28px;font-weight:800;color:var(--g)}
.dtitle{font-size:18px;font-weight:700;color:var(--txt);margin-top:4px;line-height:1.3}
.dstars{font-size:13px;color:var(--amber);margin-top:6px}
.badges{display:flex;gap:6px;margin-top:10px;flex-wrap:wrap}
.badge{font-size:10px;font-weight:700;padding:3px 10px;border-radius:var(--rfull)}
.bg{background:var(--gl);color:var(--glc)}.bb{background:var(--bl);color:var(--bc)}
.seller-row{display:flex;align-items:center;gap:10px;margin-top:14px;padding-top:14px;border-top:.5px solid var(--border)}
.ava{width:38px;height:38px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700;flex-shrink:0;overflow:hidden}
.ava img{width:100%;height:100%;object-fit:cover}
.sname{font-size:13px;font-weight:700;color:var(--txt)}
.ssub{font-size:11px;color:var(--muted);margin-top:1px}
.vtag{margin-left:auto;font-size:10px;font-weight:700;background:var(--gl);color:var(--gd);padding:3px 10px;border-radius:var(--rfull)}
.ddesc{font-size:13px;color:var(--muted);line-height:1.65;margin-top:14px}

/* ── CART ── */
.citem{display:flex;align-items:flex-start;gap:10px;padding:14px 12px;border-bottom:.5px solid var(--border)}
.cemoji{font-size:38px;flex-shrink:0;width:48px;height:48px;display:flex;align-items:center;justify-content:center;border-radius:var(--rmd);overflow:hidden}
.cemoji img{width:100%;height:100%;object-fit:cover}
.cname{font-size:13px;font-weight:700;color:var(--txt)}
.cprice{font-size:14px;color:var(--g);font-weight:700;margin-top:2px}
.qrow{display:flex;align-items:center;gap:10px;margin-top:8px}
.qbtn{width:28px;height:28px;border-radius:50%;border:.5px solid var(--border);background:var(--bg2);font-size:18px;cursor:pointer;color:var(--txt);display:flex;align-items:center;justify-content:center;line-height:1;transition:background .15s,transform .1s;font-family:inherit}
.qbtn:hover{background:var(--bg3)}.qbtn:active{transform:scale(.88)}
.qnum{font-size:14px;font-weight:700;min-width:22px;text-align:center;color:var(--txt)}
.trsh{background:none;border:none;cursor:pointer;color:var(--muted);font-size:20px;padding:4px;border-radius:var(--rmd);transition:color .15s,background .15s,transform .1s}
.trsh:hover{color:var(--red);background:rgba(226,75,74,.08)}.trsh:active{transform:scale(.9)}
.osum{margin:12px;background:var(--bg2);border-radius:var(--rlg);padding:14px}
.srow{display:flex;justify-content:space-between;font-size:13px;color:var(--muted);padding:4px 0}
.srow.tot{font-weight:700;color:var(--txt);font-size:15px;border-top:.5px solid var(--border);padding-top:12px;margin-top:6px}
.empty{flex:1;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:40px 24px;text-align:center;color:var(--muted)}
.empty i{font-size:52px;margin-bottom:14px;opacity:.35}
.empty p{font-size:14px;line-height:1.6}

/* ── CHECKOUT ── */
.slabel{font-size:11px;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.8px;margin:16px 12px 8px}
.pchoice-card{margin:0 12px 10px;display:flex;align-items:center;gap:12px;border:1.5px solid transparent;border-radius:var(--rlg);padding:14px;cursor:pointer;background:var(--bg);border:.5px solid var(--border);transition:border-color .15s,transform .1s}
.pchoice-card:hover{border-color:var(--g)}.pchoice-card:active{transform:scale(.98)}.pchoice-card.sel{border:1.5px solid var(--g)}
.pmic{width:40px;height:40px;border-radius:var(--rmd);background:var(--bg2);display:flex;align-items:center;justify-content:center;font-size:22px;flex-shrink:0}
.pmname{font-size:14px;font-weight:700;color:var(--txt)}.pmsub{font-size:11px;color:var(--muted);margin-top:2px}
.pmchk{margin-left:auto;color:var(--g);font-size:22px;display:none}.pchoice-card.sel .pmchk{display:block}

/* ── SUCCESS ── */
.sicon{width:84px;height:84px;border-radius:50%;background:var(--gl);display:flex;align-items:center;justify-content:center;margin-bottom:20px}
.sicon i{font-size:44px;color:var(--g)}

/* ── BULLETIN ── */
.bcard{margin:0 12px 10px;border:.5px solid var(--border);border-radius:var(--rlg);padding:14px;background:var(--bg);cursor:pointer;transition:transform .15s,box-shadow .15s}
.bcard:hover{transform:translateY(-1px);box-shadow:var(--shadow)}.bcard:active{transform:scale(.98)}
.btag{font-size:10px;font-weight:700;border-radius:var(--rfull);padding:3px 10px;display:inline-block;margin-bottom:7px}
.t-ev{background:var(--bl);color:var(--bc)}.t-sa{background:var(--gl);color:var(--gd)}.t-lo{background:var(--ol);color:var(--oc)}.t-sv{background:var(--pl);color:var(--pc)}
.btitle{font-size:14px;font-weight:700;color:var(--txt);line-height:1.35}.bmeta{font-size:11px;color:var(--muted);margin-top:5px}

/* ── PROFILE ── */
.phero{background:var(--g);padding:20px 16px;display:flex;align-items:center;gap:16px;flex-shrink:0}
.pava{width:64px;height:64px;border-radius:50%;background:rgba(255,255,255,.2);border:2px solid rgba(255,255,255,.5);display:flex;align-items:center;justify-content:center;font-size:24px;font-weight:800;color:#fff;overflow:hidden;cursor:pointer;position:relative;flex-shrink:0}
.pava img{width:100%;height:100%;object-fit:cover}
.pava .ov{position:absolute;inset:0;background:rgba(0,0,0,.35);display:flex;align-items:center;justify-content:center;opacity:0;transition:opacity .2s}
.pava:hover .ov{opacity:1}
.pava .ov i{color:#fff;font-size:22px}
.pname{font-size:18px;font-weight:800;color:#fff}.pemail{font-size:12px;color:rgba(255,255,255,.8);margin-top:2px}
.pvbadge{font-size:10px;font-weight:700;background:rgba(255,255,255,.2);color:#fff;padding:3px 10px;border-radius:var(--rfull);margin-top:6px;display:inline-block}
.stats{display:flex;border-bottom:.5px solid var(--border);flex-shrink:0}
.sbox{flex:1;text-align:center;padding:14px 0}.sbox+.sbox{border-left:.5px solid var(--border)}
.snum{font-size:20px;font-weight:800;color:var(--txt)}.slbl{font-size:11px;color:var(--muted);margin-top:2px}
.mitem{display:flex;align-items:center;gap:12px;padding:15px 16px;border-bottom:.5px solid var(--border);cursor:pointer;transition:background .15s}
.mitem:hover{background:var(--bg2)}.mitem i:first-child{font-size:19px;color:var(--muted);width:22px}.mlbl{flex:1;font-size:14px;color:var(--txt)}

/* ── FORMS ── */
.fg{margin-bottom:14px}
.fl{font-size:12px;font-weight:700;color:var(--muted);margin-bottom:5px;display:block}
.fi,.fsel,.fta{width:100%;background:var(--bg2);border:.5px solid var(--border);border-radius:var(--rmd);padding:11px 13px;font-size:14px;color:var(--txt);outline:none;transition:border-color .2s,box-shadow .2s;font-family:inherit}
.fi:focus,.fsel:focus,.fta:focus{border-color:var(--g);box-shadow:0 0 0 3px rgba(29,158,117,.12)}
.fi.err,.fsel.err,.fta.err{border-color:var(--red);box-shadow:0 0 0 3px rgba(226,75,74,.1)}
.err-msg{font-size:11px;color:var(--red);margin-top:4px;display:none}
.fi.err + .err-msg,.fsel.err + .err-msg,.fta.err + .err-msg{display:block}
.fsel{cursor:pointer;appearance:none;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='%236b6b67' stroke-width='2'%3E%3Cpath d='M6 9l6 6 6-6'/%3E%3C/svg%3E");background-repeat:no-repeat;background-position:right 12px center;padding-right:36px}
.fta{resize:none}

/* ── PHOTO UPLOAD ── */
.photo-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-bottom:14px}
.photo-slot{aspect-ratio:1;border-radius:var(--rmd);border:1.5px dashed var(--border);display:flex;flex-direction:column;align-items:center;justify-content:center;cursor:pointer;color:var(--muted);font-size:11px;gap:4px;transition:border-color .15s,background .15s,transform .1s;overflow:hidden;position:relative}
.photo-slot:hover{border-color:var(--g);background:var(--gl);color:var(--g)}.photo-slot:active{transform:scale(.96)}
.photo-slot.has-img{border-style:solid;border-color:var(--border)}
.photo-slot i{font-size:24px}
.photo-slot img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover}
.photo-slot .rmv{position:absolute;top:4px;right:4px;background:rgba(0,0,0,.55);border:none;border-radius:50%;width:22px;height:22px;color:#fff;font-size:13px;cursor:pointer;display:none;align-items:center;justify-content:center}
.photo-slot.has-img .rmv{display:flex}
.photo-slot .rmv:hover{background:rgba(226,75,74,.9)}

/* ── SEARCH RESULTS ── */
.no-results{padding:40px 20px;text-align:center;color:var(--muted)}
.no-results i{font-size:44px;margin-bottom:10px;display:block;opacity:.35}
.no-results p{font-size:14px}
.result-count{font-size:13px;color:var(--muted);padding:8px 12px 4px}

/* ── NOTIFICATIONS ── */
.noti{padding:14px 16px;border-bottom:.5px solid var(--border);cursor:pointer;transition:background .15s;display:flex;gap:12px;align-items:flex-start}
.noti:hover{background:var(--bg2)}.noti.unread{background:var(--gl)}
.noti-dot{width:8px;height:8px;border-radius:50%;background:var(--g);margin-top:5px;flex-shrink:0}
.noti.unread .noti-dot{display:block}.noti:not(.unread) .noti-dot{background:transparent}
.ntitle{font-size:13px;font-weight:700;color:var(--txt)}.nbody{font-size:12px;color:var(--muted);margin-top:3px;line-height:1.5}.ntime{font-size:11px;color:var(--muted);margin-top:5px}

/* ── WISHLIST ── */
.wish-list{padding:0 12px 12px}

/* ── REVIEWS ── */
.ritem{padding:14px 12px;border-bottom:.5px solid var(--border)}
.rrow{display:flex;align-items:center;gap:10px;margin-bottom:8px}
.rtxt{font-size:13px;color:var(--muted);line-height:1.6}
.star-input{display:flex;gap:4px;margin-bottom:10px}
.star-input button{background:none;border:none;font-size:28px;cursor:pointer;color:var(--border);transition:color .1s,transform .1s;line-height:1}
.star-input button:hover,.star-input button.lit{color:var(--amber)}
.star-input button:active{transform:scale(.88)}

/* ── MODAL / OVERLAY ── */
.modal-bg{position:absolute;inset:0;background:rgba(0,0,0,.48);z-index:200;display:none;align-items:flex-end;justify-content:center}
.modal-bg.open{display:flex}
.modal{background:var(--bg);border-radius:24px 24px 0 0;width:100%;max-height:85%;display:flex;flex-direction:column;overflow:hidden}
.mhdr{padding:14px 16px 12px;display:flex;align-items:center;justify-content:space-between;border-bottom:.5px solid var(--border);flex-shrink:0}
.mhdr h3{font-size:16px;font-weight:700;color:var(--txt)}
.mbody{overflow-y:auto;padding:16px;flex:1}
.close-m{background:none;border:none;cursor:pointer;color:var(--muted);font-size:22px}

/* ── TOAST ── */
.toast{position:absolute;bottom:80px;left:50%;transform:translateX(-50%) translateY(10px);background:#111110;color:#fff;font-size:13px;font-weight:600;padding:10px 20px;border-radius:var(--rfull);white-space:nowrap;opacity:0;pointer-events:none;transition:opacity .25s,transform .25s;z-index:300}
.toast.show{opacity:1;transform:translateX(-50%) translateY(0)}

/* ── ORDERS LIST ── */
.order-item{padding:14px 12px;border-bottom:.5px solid var(--border);display:flex;gap:12px;align-items:center;cursor:pointer;transition:background .15s}
.order-item:hover{background:var(--bg2)}
.order-emoji{font-size:32px;width:44px;height:44px;display:flex;align-items:center;justify-content:center;border-radius:var(--rmd);flex-shrink:0;overflow:hidden}
.order-emoji img{width:100%;height:100%;object-fit:cover}
.o-status{font-size:10px;font-weight:700;padding:2px 8px;border-radius:var(--rfull)}
.s-conf{background:var(--gl);color:var(--gd)}.s-pend{background:var(--ol);color:var(--oc)}.s-comp{background:var(--bl);color:var(--bc)}

/* ── FILTER SHEET ── */
.frange{display:flex;gap:8px;align-items:center;margin-top:6px}
.frange input[type=range]{flex:1;accent-color:var(--g)}

/* ── PROGRESS BAR ── */
.prog-bar{height:3px;background:var(--bg3);border-radius:3px;margin:8px 0}
.prog-fill{height:100%;background:var(--g);border-radius:3px;transition:width .3s}

/* ── LANDING ── */
.landing-wrap{flex:1;display:flex;flex-direction:column;align-items:center;justify-content:space-between;padding:40px 28px 32px;background:linear-gradient(165deg,var(--gd) 0%,var(--g) 55%,#2bb98a 100%);position:relative;overflow:hidden;text-align:center}
.landing-wrap::before{content:'';position:absolute;width:260px;height:260px;border-radius:50%;background:rgba(255,255,255,.08);top:-90px;right:-70px}
.landing-wrap::after{content:'';position:absolute;width:200px;height:200px;border-radius:50%;background:rgba(255,255,255,.06);bottom:60px;left:-80px}
.landing-top{display:flex;flex-direction:column;align-items:center;gap:6px;z-index:1}
.glow-logo{font-size:30px;font-weight:800;color:#fff;letter-spacing:.3px;display:flex;align-items:center;gap:8px;animation:glowPulse 2.4s ease-in-out infinite}
.glow-logo .gi{font-size:32px;filter:drop-shadow(0 0 6px rgba(255,255,255,.9));animation:glowPulse 2.4s ease-in-out infinite}
@keyframes glowPulse{
  0%,100%{text-shadow:0 0 8px rgba(255,255,255,.35),0 0 22px rgba(255,255,255,.18);}
  50%{text-shadow:0 0 18px rgba(255,255,255,.85),0 0 44px rgba(255,255,255,.5);}
}
.glow-tag{font-size:12.5px;color:rgba(255,255,255,.85);font-weight:600;letter-spacing:.4px;text-transform:uppercase}
.hero-art{z-index:1;display:flex;flex-direction:column;align-items:center;gap:18px;margin:18px 0}
.hero-ring{width:188px;height:188px;border-radius:50%;background:rgba(255,255,255,.14);border:1.5px solid rgba(255,255,255,.35);display:flex;align-items:center;justify-content:center;position:relative;box-shadow:0 0 50px rgba(255,255,255,.22)}
.hero-ring .hr-center{font-size:54px;filter:drop-shadow(0 4px 10px rgba(0,0,0,.18))}
.hero-chip{position:absolute;width:46px;height:46px;border-radius:14px;background:#fff;display:flex;align-items:center;justify-content:center;font-size:22px;box-shadow:0 6px 16px rgba(0,0,0,.18);animation:floaty 3.2s ease-in-out infinite}
.hero-chip.c1{top:-10px;left:6px;animation-delay:0s}
.hero-chip.c2{top:-6px;right:0;animation-delay:.5s}
.hero-chip.c3{bottom:-12px;left:-10px;animation-delay:1s}
.hero-chip.c4{bottom:-8px;right:-6px;animation-delay:1.5s}
@keyframes floaty{0%,100%{transform:translateY(0)}50%{transform:translateY(-7px)}}
.hero-copy h1{font-size:19px;font-weight:800;color:#fff;line-height:1.35}
.hero-copy p{font-size:13px;color:rgba(255,255,255,.82);margin-top:8px;line-height:1.6;max-width:280px}
.landing-bottom{width:100%;z-index:1;display:flex;flex-direction:column;gap:10px}
.btn-landing{background:#fff;color:var(--gd);border:none;border-radius:var(--rfull);padding:14px;font-size:15px;font-weight:700;cursor:pointer;width:100%;transition:transform .1s,box-shadow .15s;box-shadow:0 8px 22px rgba(0,0,0,.18)}
.btn-landing:active{transform:scale(.97)}
.btn-landing-outline{background:rgba(255,255,255,.12);color:#fff;border:1.5px solid rgba(255,255,255,.55);border-radius:var(--rfull);padding:13px;font-size:14px;font-weight:600;cursor:pointer;width:100%;transition:background .15s,transform .1s}
.btn-landing-outline:hover{background:rgba(255,255,255,.22)}
.btn-landing-outline:active{transform:scale(.97)}
.guest-link{font-size:12.5px;color:rgba(255,255,255,.78);text-decoration:underline;cursor:pointer;margin-top:2px;background:none;border:none;font-family:inherit}

/* ── AUTH ── */
.auth-wrap{flex:1;display:flex;flex-direction:column;overflow:hidden}
.auth-head{padding:28px 24px 4px;flex-shrink:0}
.auth-head .gi-sm{font-size:24px}
.auth-head h1{font-size:21px;font-weight:800;color:var(--txt);margin-top:10px}
.auth-head p{font-size:13px;color:var(--muted);margin-top:4px}
.auth-tabs{display:flex;gap:6px;margin:18px 24px 0;background:var(--bg2);border-radius:var(--rfull);padding:4px}
.auth-tab{flex:1;text-align:center;padding:9px 0;border-radius:var(--rfull);font-size:13px;font-weight:700;color:var(--muted);cursor:pointer;background:none;border:none;font-family:inherit;transition:background .15s,color .15s}
.auth-tab.active{background:var(--g);color:#fff}
.auth-body{flex:1;overflow-y:auto;padding:18px 24px 24px}
.auth-form{display:none}
.auth-form.active{display:block}
.pw-wrap{position:relative}
.pw-toggle{position:absolute;right:12px;top:50%;transform:translateY(-50%);background:none;border:none;color:var(--muted);cursor:pointer;font-size:17px;padding:4px}
.auth-divider{display:flex;align-items:center;gap:10px;margin:18px 0;color:var(--muted);font-size:11px}
.auth-divider::before,.auth-divider::after{content:'';flex:1;height:1px;background:var(--border)}
.auth-switch{text-align:center;font-size:13px;color:var(--muted);margin-top:14px}
.auth-switch a{color:var(--g);font-weight:700;cursor:pointer;text-decoration:none}

/* ── GUEST GATE MODAL ── */
.guest-gate-modal{background:var(--bg);border-radius:24px 24px 0 0;width:100%;padding:28px 24px 32px;text-align:center}
.guest-gate-icon{font-size:48px;margin-bottom:12px}
.guest-gate-modal h3{font-size:19px;font-weight:800;color:var(--txt);margin-bottom:8px}
.guest-gate-modal p{font-size:13px;color:var(--muted);line-height:1.6;margin-bottom:22px}

/* ── PAYMENT PROCESSING ── */
.pay-processing{position:absolute;inset:0;background:var(--bg);z-index:150;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:32px;text-align:center;opacity:0;pointer-events:none;transition:opacity .3s}
.pay-processing.show{opacity:1;pointer-events:all}
.pay-spinner{width:72px;height:72px;border-radius:50%;border:4px solid var(--bg3);border-top-color:var(--g);animation:spin .8s linear infinite;margin-bottom:20px}
@keyframes spin{to{transform:rotate(360deg)}}
.pay-status{font-size:15px;font-weight:700;color:var(--txt);margin-bottom:6px}
.pay-sub{font-size:12px;color:var(--muted)}

/* ── ENHANCED SUCCESS ── */
.success-wrap{flex:1;display:flex;flex-direction:column;overflow:hidden;position:relative}
.confetti-canvas{position:absolute;inset:0;pointer-events:none;z-index:10}
.success-body{flex:1;overflow-y:auto;padding:28px 20px 32px;text-align:center;position:relative;z-index:11}
.success-anim{width:90px;height:90px;border-radius:50%;background:var(--gl);display:flex;align-items:center;justify-content:center;margin:0 auto 20px;animation:popIn .5s cubic-bezier(.34,1.56,.64,1)}
@keyframes popIn{0%{transform:scale(0)}100%{transform:scale(1)}}
.success-anim i{font-size:46px;color:var(--g)}
.success-title{font-size:24px;font-weight:800;color:var(--txt);margin-bottom:6px}
.success-subtitle{font-size:14px;color:var(--muted);line-height:1.6;margin-bottom:22px}
.receipt-card{background:var(--bg2);border:.5px solid var(--border);border-radius:var(--rlg);padding:18px;text-align:left;margin-bottom:20px}
.receipt-title{font-size:11px;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.8px;margin-bottom:12px}
.receipt-row{display:flex;justify-content:space-between;align-items:baseline;font-size:13px;color:var(--txt);padding:4px 0}
.receipt-row .rl{color:var(--muted)}
.receipt-row.total{font-weight:800;font-size:15px;border-top:.5px solid var(--border);margin-top:8px;padding-top:12px}
.receipt-row.total .rv{color:var(--g)}
.receipt-divider{border:none;border-top:.5px dashed var(--border);margin:10px 0}
.order-badge{display:inline-flex;align-items:center;gap:6px;background:var(--gl);border-radius:var(--rfull);padding:6px 14px;font-size:12px;font-weight:700;color:var(--gd);margin-bottom:18px}
.delivery-info{background:var(--bl);border-radius:var(--rlg);padding:14px;text-align:left;margin-bottom:20px;display:flex;gap:12px;align-items:center}
.delivery-info i{font-size:22px;color:var(--bc);flex-shrink:0}
.di-title{font-size:13px;font-weight:700;color:var(--txt)}
.di-sub{font-size:12px;color:var(--muted);margin-top:2px}
</style>

</head>
<body>

<div class="page-label">Community Store · Campus Marketplace — Full Prototype</div>

<div class="phone" id="app">
  <div class="sbar">
    <span>9:41</span>
    <span>Community Store</span>
    <div style="display:flex;gap:4px;align-items:center">
      <i class="ti ti-wifi" style="font-size:13px"></i>
      <i class="ti ti-battery-2" style="font-size:13px"></i>
    </div>
  </div>

  <!-- ══════════════════ LANDING / FRONT PAGE ══════════════════ -->
  <div class="screen active" id="s-landing">
    <div class="landing-wrap">
      <div class="landing-top">
        <div class="glow-logo"><span class="gi">🛍️</span> Community Store</div>
        <div class="glow-tag">Campus Marketplace</div>
      </div>
      <div class="hero-art">
        <div class="hero-ring">
          <span class="hr-center">🎓</span>
          <div class="hero-chip c1">📚</div>
          <div class="hero-chip c2">💻</div>
          <div class="hero-chip c3">🍱</div>
          <div class="hero-chip c4">👕</div>
        </div>
        <div class="hero-copy">
          <h1>Buy, sell &amp; connect<br>with your campus</h1>
          <p>Textbooks, electronics, food, services & more — bought and sold by verified students near you.</p>
        </div>
      </div>
      <div class="landing-bottom">
        <button class="btn-landing" onclick="go('auth');showAuthTab('signup')"><i class="ti ti-rocket"></i> Get started</button>
        <button class="btn-landing-outline" onclick="go('auth');showAuthTab('signin')">I already have an account</button>
        <button class="guest-link" onclick="continueAsGuest()">Continue as guest</button>
      </div>
    </div>
  </div>

  <!-- ══════════════════ SIGN IN / SIGN UP ══════════════════ -->
  <div class="screen" id="s-auth">
    <div class="auth-wrap">
      <div class="auth-head">
        <div class="hdr-row" style="margin-bottom:6px">
          <button class="back" style="background:var(--bg2);color:var(--txt)" onclick="go('landing')"><i class="ti ti-arrow-left"></i></button>
        </div>
        <span class="gi-sm">🛍️</span>
        <h1 id="auth-title">Create your account</h1>
        <p id="auth-sub">Join your campus marketplace in seconds.</p>
      </div>
      <div class="auth-tabs">
        <button class="auth-tab active" id="tab-signup" onclick="showAuthTab('signup')">Sign up</button>
        <button class="auth-tab" id="tab-signin" onclick="showAuthTab('signin')">Sign in</button>
      </div>
      <div class="auth-body">
        <!-- SIGN UP -->
        <div class="auth-form active" id="form-signup">
          <div class="fg">
            <label class="fl">Full name *</label>
            <input class="fi" id="su-name" type="text" placeholder="e.g. Precious Mokoena">
            <span class="err-msg">Please enter your full name</span>
          </div>
          <div class="fg">
            <label class="fl">University email *</label>
            <input class="fi" id="su-email" type="email" placeholder="student@university.ac.za">
            <span class="err-msg">Please enter a valid university email</span>
          </div>
          <div class="fg">
            <label class="fl">Password *</label>
            <div class="pw-wrap">
              <input class="fi" id="su-pw" type="password" placeholder="At least 8 characters">
              <button type="button" class="pw-toggle" onclick="togglePw('su-pw',this)"><i class="ti ti-eye"></i></button>
            </div>
            <span class="err-msg">Password must be at least 8 characters</span>
          </div>
          <div class="fg">
            <label class="fl">Campus / Faculty</label>
            <input class="fi" id="su-campus" type="text" placeholder="e.g. Engineering, TUT Pretoria">
          </div>
          <button class="btn btn-g" onclick="handleSignup()"><i class="ti ti-user-plus"></i> Create account</button>
          <div class="auth-switch">Already have an account? <a onclick="showAuthTab('signin')">Sign in</a></div>
        </div>
        <!-- SIGN IN -->
        <div class="auth-form" id="form-signin">
          <div class="fg">
            <label class="fl">University email *</label>
            <input class="fi" id="si-email" type="email" placeholder="student@university.ac.za">
            <span class="err-msg">Please enter your email</span>
          </div>
          <div class="fg">
            <label class="fl">Password *</label>
            <div class="pw-wrap">
              <input class="fi" id="si-pw" type="password" placeholder="••••••••">
              <button type="button" class="pw-toggle" onclick="togglePw('si-pw',this)"><i class="ti ti-eye"></i></button>
            </div>
            <span class="err-msg">Please enter your password</span>
          </div>
          <div style="text-align:right;margin:-4px 0 16px">
            <a style="font-size:12px;color:var(--g);font-weight:600;cursor:pointer;text-decoration:none" onclick="showToast('Password reset link sent ✓')">Forgot password?</a>
          </div>
          <button class="btn btn-g" onclick="handleSignin()"><i class="ti ti-login-2"></i> Sign in</button>
          <div class="auth-divider">or</div>
          <button class="btn btn-s" onclick="continueAsGuest()"><i class="ti ti-user"></i> Continue as guest</button>
          <div class="auth-switch">New here? <a onclick="showAuthTab('signup')">Create an account</a></div>
        </div>
      </div>
    </div>
  </div>

  <!-- ══════════════════ HOME ══════════════════ -->
  <div class="screen" id="s-home">
    <div class="hdr" style="padding-bottom:0">
      <div style="display:flex;justify-content:space-between;align-items:center;padding-bottom:14px">
        <div>
          <div style="font-size:12px;color:rgba(255,255,255,.8)">Good morning 👋</div>
          <div style="font-size:18px;font-weight:800;color:#fff" id="home-username">Precious</div>
        </div>
        <button class="ibtn" onclick="go('notifications')" style="position:relative" aria-label="Notifications">
          <i class="ti ti-bell"></i>
          <span id="notif-dot" style="position:absolute;top:7px;right:8px;width:8px;height:8px;background:var(--amber);border-radius:50%;border:2px solid var(--g)"></span>
        </button>
      </div>
    </div>
    <div class="scroll" id="home-scroll">
      <div class="searchbar" onclick="go('search');document.getElementById('main-search').focus()">
        <i class="ti ti-search"></i>
        <input id="home-search-fake" type="text" placeholder="Search products, vendors…" readonly style="cursor:pointer">
      </div>
      <div class="chips" id="home-chips">
        <button class="chip active" onclick="homeFilter(this,'All')">All</button>
        <button class="chip" onclick="homeFilter(this,'Books')">📚 Books</button>
        <button class="chip" onclick="homeFilter(this,'Electronics')">💻 Electronics</button>
        <button class="chip" onclick="homeFilter(this,'Food')">🍱 Food</button>
        <button class="chip" onclick="homeFilter(this,'Services')">🛠 Services</button>
        <button class="chip" onclick="homeFilter(this,'Clothing')">👕 Clothing</button>
      </div>
      <div class="banner">
        <h3>Campus sale — up to 40% off</h3>
        <p>Verified student vendors only. Ends Sunday.</p>
        <button class="banner-btn" onclick="go('search')">Browse deals →</button>
      </div>
      <div class="stitle">Featured listings <a onclick="go('search')">See all</a></div>
      <div class="pgrid" id="home-grid"></div>
      <div class="stitle">Near you <a onclick="go('search')">See all</a></div>
      <div class="pgrid" id="home-grid2" style="padding-bottom:20px"></div>
    </div>
  </div>

  <!-- ══════════════════ SEARCH ══════════════════ -->
  <div class="screen" id="s-search">
    <div class="hdr">
      <div class="hdr-row">
        <button class="back" onclick="back()" aria-label="Back"><i class="ti ti-arrow-left"></i></button>
        <div class="searchbar" style="margin:0;flex:1;background:rgba(255,255,255,.18);border-color:rgba(255,255,255,.25)">
          <i class="ti ti-search" style="color:rgba(255,255,255,.7)"></i>
          <input id="main-search" type="text" placeholder="Search products, vendors…"
            style="color:#fff;background:transparent"
            oninput="doSearch(this.value)"
            onfocus="this.parentElement.style.borderColor='rgba(255,255,255,.6)'"
            onblur="this.parentElement.style.borderColor='rgba(255,255,255,.25)'">
          <button class="clear-btn" onclick="clearSearch()" aria-label="Clear search" style="color:rgba(255,255,255,.7)"><i class="ti ti-x"></i></button>
        </div>
        <button class="ibtn" onclick="openModal('filter-modal')" aria-label="Filters"><i class="ti ti-adjustments-horizontal"></i></button>
      </div>
    </div>
    <div class="chips" style="padding:8px 12px 6px" id="search-chips">
      <button class="chip active" onclick="searchFilter(this,'All')">All</button>
      <button class="chip" onclick="searchFilter(this,'Books')">📚 Books</button>
      <button class="chip" onclick="searchFilter(this,'Electronics')">💻 Electronics</button>
      <button class="chip" onclick="searchFilter(this,'Food')">🍱 Food</button>
      <button class="chip" onclick="searchFilter(this,'Services')">🛠 Services</button>
      <button class="chip" onclick="searchFilter(this,'Clothing')">👕 Clothing</button>
    </div>
    <div class="scroll">
      <div id="search-trending" style="padding:0 12px">
        <div style="font-size:13px;font-weight:700;color:var(--muted);margin:8px 0 10px">Trending</div>
        <div style="display:flex;flex-wrap:wrap;gap:8px;margin-bottom:16px">
          <button class="chip" onclick="setSearch('Textbooks')">📚 Textbooks</button>
          <button class="chip" onclick="setSearch('Calculator')">🧮 Calculator</button>
          <button class="chip" onclick="setSearch('Food')">🍱 Food</button>
          <button class="chip" onclick="setSearch('Tutoring')">📝 Tutoring</button>
          <button class="chip" onclick="setSearch('Laptop')">💻 Laptop</button>
          <button class="chip" onclick="setSearch('Hoodie')">👕 Hoodie</button>
        </div>
      </div>
      <div id="search-results" style="display:none">
        <div class="result-count" id="result-count">6 listings</div>
        <div class="pgrid" id="result-grid"></div>
        <div class="no-results" id="no-results" style="display:none">
          <i class="ti ti-search-off"></i>
          <p>No listings found.<br>Try a different keyword.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- ══════════════════ PRODUCT DETAIL ══════════════════ -->
  <div class="screen" id="s-product">
    <div class="hdr">
      <div class="hdr-row">
        <button class="back" onclick="back()" aria-label="Back"><i class="ti ti-arrow-left"></i></button>
        <span class="hdr-title" id="d-htitle">Product</span>
        <button class="ibtn" onclick="toggleWishlistCurrent()" id="d-wish-btn" aria-label="Wishlist"><i class="ti ti-heart"></i></button>
        <button class="ibtn" onclick="showToast('Link copied to clipboard!')" aria-label="Share"><i class="ti ti-share"></i></button>
      </div>
    </div>
    <div class="scroll" style="padding-bottom:16px">
      <div class="dimg" id="d-img-bg">
        <span id="d-emoji">🧮</span>
        <img id="d-img-uploaded" class="dimg-uploaded" style="display:none" alt="Product">
      </div>
      <div class="dbody">
        <div class="dprice" id="d-price">R 180</div>
        <div class="dtitle" id="d-title">Product</div>
        <div class="dstars" id="d-stars">★★★★★</div>
        <div class="badges"><span class="badge bg" id="d-cond">Used – Good</span><span class="badge bb">Campus pickup</span></div>
        <div class="seller-row">
          <div class="ava" id="d-ava" style="background:var(--gl);color:var(--gd)">
            <img id="d-ava-img" style="display:none" alt="seller">
            <span id="d-ava-txt">SM</span>
          </div>
          <div><div class="sname" id="d-seller">Sipho M.</div><div class="ssub" id="d-seller-sub">Student vendor</div></div>
          <span class="vtag">✓ Verified</span>
        </div>
        <div class="ddesc" id="d-desc">Description</div>
        <button class="btn btn-g" onclick="addToCart(); showToast('Added to cart ✓')"><i class="ti ti-shopping-cart"></i> Add to cart</button>
        <button class="btn btn-s" onclick="toggleWishlistCurrent()"><i class="ti ti-heart" id="d-wish-icon"></i> <span id="d-wish-lbl">Save to wishlist</span></button>
        <button class="btn btn-s" onclick="if(requireAuth('Sign in to message sellers','Create an account to contact sellers directly.'))openModal('msg-modal')"><i class="ti ti-message"></i> Message seller</button>
      </div>
    </div>
  </div>

  <!-- ══════════════════ CART ══════════════════ -->
  <div class="screen" id="s-cart">
    <div class="hdr"><h2>My cart</h2><p id="cart-sub-hdr">0 items</p></div>
    <div style="flex:1;display:flex;flex-direction:column;min-height:0;overflow:hidden">
      <div class="empty" id="cart-empty">
        <i class="ti ti-shopping-cart"></i>
        <p>Your cart is empty.<br>Browse listings to add items.</p>
        <button class="btn btn-g btn-sm" style="margin-top:20px" onclick="go('home')">Browse listings</button>
      </div>
      <div id="cart-has" style="display:none;flex-direction:column;flex:1;min-height:0;overflow:hidden">
        <div class="scroll" id="cart-items-list"></div>
        <div style="padding:0 0 12px;flex-shrink:0">
          <div class="osum" id="cart-summary"></div>
          <div style="padding:0 12px">
            <button class="btn btn-g" onclick="go('checkout')"><i class="ti ti-lock"></i> Proceed to checkout</button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- ══════════════════ CHECKOUT ══════════════════ -->
  <div class="screen" id="s-checkout">
    <div class="hdr"><div class="hdr-row"><button class="back" onclick="back()"><i class="ti ti-arrow-left"></i></button><span class="hdr-title">Checkout</span></div></div>
    <div class="scroll" style="padding-bottom:16px">
      <div class="slabel">Delivery</div>
      <div style="margin:0 12px;border:.5px solid var(--border);border-radius:var(--rlg);padding:14px;background:var(--bg)">
        <div style="display:flex;align-items:center;gap:10px">
          <div style="width:38px;height:38px;border-radius:var(--rmd);background:var(--gl);display:flex;align-items:center;justify-content:center;font-size:20px">📍</div>
          <div><div style="font-size:14px;font-weight:700;color:var(--txt)">Pick-up on campus</div><div style="font-size:12px;color:var(--muted);margin-top:2px">Building 5, Student Hub · Mon–Fri 08:00–17:00</div></div>
          <i class="ti ti-circle-check" style="margin-left:auto;color:var(--g);font-size:22px"></i>
        </div>
      </div>
      <div class="slabel">Payment method</div>
      <div class="pchoice-card sel" id="pm-payfast" onclick="selPM('payfast')" role="radio" tabindex="0">
        <div class="pmic">💳</div><div><div class="pmname">PayFast</div><div class="pmsub">Card / EFT payment</div></div>
        <i class="ti ti-circle-check pmchk"></i>
      </div>
      <div class="pchoice-card" id="pm-snapscan" onclick="selPM('snapscan')" role="radio" tabindex="0">
        <div class="pmic">📱</div><div><div class="pmname">SnapScan</div><div class="pmsub">Scan QR to pay</div></div>
        <i class="ti ti-circle-check pmchk"></i>
      </div>
      <div class="pchoice-card" id="pm-escrow" onclick="selPM('escrow')" role="radio" tabindex="0">
        <div class="pmic">🔒</div><div><div class="pmname">Escrow</div><div class="pmsub">Released on pickup confirmation</div></div>
        <i class="ti ti-circle-check pmchk"></i>
      </div>
      <div class="slabel">Order summary</div>
      <div class="osum" style="margin:0 12px 16px" id="co-summary"></div>
      <div style="padding:0 12px">
        <button class="btn btn-g" onclick="confirmAndPay()"><i class="ti ti-lock"></i> Confirm & pay <span id="co-total-btn"></span></button>
      </div>
    </div>
  </div>

  <!-- ══════════════════ SUCCESS ══════════════════ -->
  <div class="screen" id="s-success">
    <div class="success-wrap">
      <canvas class="confetti-canvas" id="confetti-canvas"></canvas>
      <div class="success-body">
        <div class="success-anim"><i class="ti ti-circle-check"></i></div>
        <div class="success-title">Payment confirmed! 🎉</div>
        <div class="success-subtitle" id="success-msg">Your payment is secured. The seller will confirm within 24 hours.</div>
        <div class="order-badge"><i class="ti ti-receipt"></i> <span id="success-order-num">Order #CS-20260001</span></div>
        <div class="receipt-card">
          <div class="receipt-title">Receipt</div>
          <div id="receipt-items"></div>
          <hr class="receipt-divider">
          <div class="receipt-row"><span class="rl">Subtotal</span><span class="rv" id="receipt-sub"></span></div>
          <div class="receipt-row"><span class="rl">Platform fee (2%)</span><span class="rv" id="receipt-fee"></span></div>
          <div class="receipt-row"><span class="rl">Campus pickup</span><span class="rv" style="color:var(--g);font-weight:700">Free</span></div>
          <div class="receipt-row total"><span>Total paid</span><span class="rv" id="receipt-total"></span></div>
        </div>
        <div class="delivery-info">
          <i class="ti ti-map-pin"></i>
          <div><div class="di-title">Collect at Building 5, Student Hub</div><div class="di-sub">Mon – Fri · 08:00 – 17:00 · Seller will confirm time</div></div>
        </div>
        <button class="btn btn-g" onclick="go('home');clearCart()"><i class="ti ti-home"></i> Back to home</button>
        <button class="btn btn-s" onclick="go('orders')"><i class="ti ti-package"></i> Track my order</button>
      </div>
    </div>
  </div>

  <!-- ══════════════════ BULLETIN ══════════════════ -->
  <div class="screen" id="s-bulletin">
    <div class="hdr"><h2>Bulletin board</h2><p>Campus announcements & events</p></div>
    <div class="scroll" style="padding-top:10px">
      <div class="chips" id="bull-chips">
        <button class="chip active" onclick="bullFilter(this,'All')">All</button>
        <button class="chip" onclick="bullFilter(this,'Event')">📅 Events</button>
        <button class="chip" onclick="bullFilter(this,'For sale')">🛍 For sale</button>
        <button class="chip" onclick="bullFilter(this,'Service')">🛠 Services</button>
        <button class="chip" onclick="bullFilter(this,'Lost & found')">🔍 Lost</button>
      </div>
      <div id="bull-list"></div>
      <button class="btn btn-s" style="margin:4px 12px 16px;width:calc(100% - 24px);margin-top:0;display:flex;align-items:center;justify-content:center;gap:6px;border:1.5px dashed var(--border)" onclick="isGuest?requireAuth('Sign in to post','Sign in to share announcements with your campus.'):go('post-bulletin')">
        <i class="ti ti-plus"></i> Post an announcement
      </button>
    </div>
  </div>

  <!-- ══════════════════ POST BULLETIN ══════════════════ -->
  <div class="screen" id="s-post-bulletin">
    <div class="hdr"><div class="hdr-row"><button class="back" onclick="back()"><i class="ti ti-arrow-left"></i></button><span class="hdr-title">New announcement</span></div></div>
    <div class="scroll" style="padding:16px">
      <div class="fg">
        <label class="fl">Category *</label>
        <select class="fsel" id="pb-cat">
          <option value="">Select category…</option>
          <option>Event</option><option>For sale</option><option>Service</option><option>Lost &amp; found</option><option>Fundraiser</option>
        </select>
        <span class="err-msg">Please select a category</span>
      </div>
      <div class="fg">
        <label class="fl">Title *</label>
        <input class="fi" id="pb-title" type="text" placeholder="Brief headline for your announcement" maxlength="80">
        <span class="err-msg">Title is required</span>
      </div>
      <div class="fg">
        <label class="fl">Details *</label>
        <textarea class="fta" id="pb-details" rows="4" placeholder="Add location, time, contact info, price…"></textarea>
        <span class="err-msg">Please add some details</span>
      </div>
      <div class="fg">
        <label class="fl">Contact (optional)</label>
        <input class="fi" id="pb-contact" type="text" placeholder="Phone, email, or WhatsApp">
      </div>
      <button class="btn btn-g" onclick="submitBulletin()"><i class="ti ti-send"></i> Post announcement</button>
      <button class="btn btn-s" onclick="confirmDiscardBulletin()">Cancel</button>
    </div>
  </div>

  <!-- ══════════════════ PROFILE ══════════════════ -->
  <div class="screen" id="s-profile">
    <div class="phero">
      <div class="pava" id="profile-ava" onclick="triggerAvatarUpload()" title="Change photo">
        <img id="profile-ava-img" style="display:none" alt="Profile">
        <span id="profile-ava-txt">PM</span>
        <div class="ov"><i class="ti ti-camera"></i></div>
      </div>
      <div>
        <div class="pname" id="profile-name">Precious Mokoena</div>
        <div class="pemail" id="profile-email">precious@tut.ac.za</div>
        <span class="pvbadge">✓ University verified</span>
      </div>
    </div>
    <div class="stats">
      <div class="sbox"><div class="snum" id="stat-orders">3</div><div class="slbl">Orders</div></div>
      <div class="sbox"><div class="snum" id="stat-listings">1</div><div class="slbl">Listings</div></div>
      <div class="sbox"><div class="snum" style="color:var(--amber)" id="stat-rating">4.8★</div><div class="slbl">Rating</div></div>
    </div>
    <div class="scroll">
      <div class="mitem" onclick="go('orders')"><i class="ti ti-shopping-bag"></i><span class="mlbl">My orders</span><i class="ti ti-chevron-right" style="color:var(--border)"></i></div>
      <div class="mitem" onclick="go('sell')"><i class="ti ti-tag"></i><span class="mlbl">My listings</span><i class="ti ti-chevron-right" style="color:var(--border)"></i></div>
      <div class="mitem" onclick="go('wishlist')"><i class="ti ti-heart"></i><span class="mlbl">Wishlist <span id="wish-count-badge" style="font-size:11px;background:var(--g);color:#fff;border-radius:10px;padding:1px 7px;display:none"></span></span><i class="ti ti-chevron-right" style="color:var(--border)"></i></div>
      <div class="mitem" onclick="go('ratings')"><i class="ti ti-star"></i><span class="mlbl">Ratings & reviews</span><i class="ti ti-chevron-right" style="color:var(--border)"></i></div>
      <div class="mitem" onclick="go('notifications')"><i class="ti ti-bell"></i><span class="mlbl">Notifications</span><i class="ti ti-chevron-right" style="color:var(--border)"></i></div>
      <div class="mitem" onclick="go('account-settings')"><i class="ti ti-settings"></i><span class="mlbl">Account settings</span><i class="ti ti-chevron-right" style="color:var(--border)"></i></div>
      <div class="mitem" onclick="go('privacy')"><i class="ti ti-lock"></i><span class="mlbl">Privacy & security</span><i class="ti ti-chevron-right" style="color:var(--border)"></i></div>
      <div class="mitem" onclick="confirmSignOut()"><i class="ti ti-logout" style="color:var(--red)"></i><span class="mlbl" style="color:var(--red)">Sign out</span><i class="ti ti-chevron-right" style="color:var(--border)"></i></div>
    </div>
  </div>

  <!-- ══════════════════ SELL / CREATE LISTING ══════════════════ -->
  <div class="screen" id="s-sell">
    <div class="hdr"><div class="hdr-row"><button class="back" onclick="back()"><i class="ti ti-arrow-left"></i></button><span class="hdr-title">Create listing</span></div></div>
    <div class="scroll" style="padding:16px">
      <div class="fg">
        <label class="fl">Photos (up to 5)</label>
        <div class="photo-grid" id="sell-photos">
          <div class="photo-slot" id="slot-0" onclick="triggerPhotoUpload(0)">
            <i class="ti ti-camera-plus"></i><span>Add photo</span>
            <button class="rmv" onclick="removePhoto(event,0)"><i class="ti ti-x"></i></button>
          </div>
          <div class="photo-slot" id="slot-1" onclick="triggerPhotoUpload(1)">
            <i class="ti ti-plus"></i><span>Add</span>
            <button class="rmv" onclick="removePhoto(event,1)"><i class="ti ti-x"></i></button>
          </div>
          <div class="photo-slot" id="slot-2" onclick="triggerPhotoUpload(2)">
            <i class="ti ti-plus"></i><span>Add</span>
            <button class="rmv" onclick="removePhoto(event,2)"><i class="ti ti-x"></i></button>
          </div>
          <div class="photo-slot" id="slot-3" onclick="triggerPhotoUpload(3)">
            <i class="ti ti-plus"></i><span>Add</span>
            <button class="rmv" onclick="removePhoto(event,3)"><i class="ti ti-x"></i></button>
          </div>
          <div class="photo-slot" id="slot-4" onclick="triggerPhotoUpload(4)">
            <i class="ti ti-plus"></i><span>Add</span>
            <button class="rmv" onclick="removePhoto(event,4)"><i class="ti ti-x"></i></button>
          </div>
        </div>
      </div>
      <div class="fg">
        <label class="fl">Title *</label>
        <input class="fi" id="s-title" type="text" placeholder="What are you selling?" maxlength="80">
        <span class="err-msg">Title is required</span>
      </div>
      <div class="fg">
        <label class="fl">Category *</label>
        <select class="fsel" id="s-cat">
          <option value="">Select category…</option>
          <option>📚 Books</option><option>💻 Electronics</option><option>🍱 Food</option>
          <option>👕 Clothing</option><option>🛠 Services</option><option>Other</option>
        </select>
        <span class="err-msg">Please select a category</span>
      </div>
      <div class="fg">
        <label class="fl">Price (R) *</label>
        <input class="fi" id="s-price" type="number" placeholder="0.00" min="0" step="0.01">
        <span class="err-msg">Please enter a valid price</span>
      </div>
      <div class="fg">
        <label class="fl">Condition *</label>
        <select class="fsel" id="s-cond">
          <option value="">Select condition…</option>
          <option>New</option><option>Used – Like new</option><option>Used – Good</option><option>Used – Fair</option>
        </select>
        <span class="err-msg">Please select a condition</span>
      </div>
      <div class="fg">
        <label class="fl">Description *</label>
        <textarea class="fta" id="s-desc" rows="4" placeholder="Describe your item, what's included, any flaws…"></textarea>
        <span class="err-msg">Description is required</span>
      </div>
      <div class="fg">
        <label class="fl">Location on campus</label>
        <input class="fi" id="s-loc" type="text" placeholder="e.g. Building 5, Engineering Block">
      </div>
      <button class="btn btn-g" onclick="publishListing()"><i class="ti ti-upload"></i> Publish listing</button>
      <button class="btn btn-s" onclick="showToast('Draft saved')">Save as draft</button>
      <button class="btn btn-s" onclick="confirmDiscardSell()">Cancel</button>
    </div>
  </div>

  <!-- ══════════════════ MY ORDERS ══════════════════ -->
  <div class="screen" id="s-orders">
    <div class="hdr"><div class="hdr-row"><button class="back" onclick="back()"><i class="ti ti-arrow-left"></i></button><span class="hdr-title">My orders</span></div></div>
    <div class="scroll" id="orders-list"></div>
  </div>

  <!-- ══════════════════ WISHLIST ══════════════════ -->
  <div class="screen" id="s-wishlist">
    <div class="hdr"><div class="hdr-row"><button class="back" onclick="back()"><i class="ti ti-arrow-left"></i></button><span class="hdr-title">Wishlist</span></div></div>
    <div class="scroll">
      <div class="pgrid" id="wish-grid" style="padding-top:10px"></div>
      <div class="empty" id="wish-empty" style="display:none">
        <i class="ti ti-heart-off"></i>
        <p>Your wishlist is empty.<br>Tap ♡ on any listing to save it.</p>
      </div>
    </div>
  </div>

  <!-- ══════════════════ RATINGS ══════════════════ -->
  <div class="screen" id="s-ratings">
    <div class="hdr"><div class="hdr-row"><button class="back" onclick="back()"><i class="ti ti-arrow-left"></i></button><span class="hdr-title">Ratings & reviews</span></div></div>
    <div class="scroll">
      <div style="text-align:center;padding:20px 0;border-bottom:.5px solid var(--border)">
        <div style="font-size:50px;font-weight:800;color:var(--txt)">4.8</div>
        <div style="color:var(--amber);font-size:24px;margin:4px 0">★★★★★</div>
        <div style="font-size:13px;color:var(--muted)">Based on 3 reviews</div>
      </div>
      <div id="reviews-list"></div>
      <div style="padding:12px">
        <button class="btn btn-s" onclick="openModal('review-modal')"><i class="ti ti-star"></i> Leave a review</button>
      </div>
    </div>
  </div>

  <!-- ══════════════════ NOTIFICATIONS ══════════════════ -->
  <div class="screen" id="s-notifications">
    <div class="hdr">
      <div class="hdr-row">
        <button class="back" onclick="back()"><i class="ti ti-arrow-left"></i></button>
        <span class="hdr-title">Notifications</span>
        <button class="ibtn" onclick="markAllRead()" aria-label="Mark all read"><i class="ti ti-checks"></i></button>
      </div>
    </div>
    <div class="scroll" id="notif-list"></div>
  </div>

  <!-- ══════════════════ ACCOUNT SETTINGS ══════════════════ -->
  <div class="screen" id="s-account-settings">
    <div class="hdr"><div class="hdr-row"><button class="back" onclick="back()"><i class="ti ti-arrow-left"></i></button><span class="hdr-title">Account settings</span></div></div>
    <div class="scroll" style="padding:16px">
      <div class="fg">
        <label class="fl">Full name</label>
        <input class="fi" id="acc-name" type="text" placeholder="Full name">
      </div>
      <div class="fg">
        <label class="fl">Email address</label>
        <input class="fi" id="acc-email" type="email" placeholder="student@university.ac.za">
      </div>
      <div class="fg">
        <label class="fl">Phone number</label>
        <input class="fi" id="acc-phone" type="tel" placeholder="+27 00 000 0000">
      </div>
      <div class="fg">
        <label class="fl">Campus / Faculty</label>
        <input class="fi" id="acc-campus" type="text" placeholder="e.g. Engineering, TUT Pretoria">
      </div>
      <div class="fg">
        <label class="fl">Profile photo</label>
        <div style="display:flex;align-items:center;gap:12px;margin-top:4px">
          <div class="ava" id="acc-ava-preview" style="background:var(--gl);color:var(--gd);width:48px;height:48px;font-size:16px">
            <img id="acc-ava-img" style="display:none;width:100%;height:100%;object-fit:cover" alt="Profile">
            <span id="acc-ava-txt">PM</span>
          </div>
          <button class="btn btn-s btn-sm" onclick="triggerAvatarUpload()"><i class="ti ti-upload"></i> Upload photo</button>
        </div>
      </div>
      <button class="btn btn-g" onclick="saveAccountSettings()"><i class="ti ti-device-floppy"></i> Save changes</button>
      <button class="btn btn-s" onclick="confirmDiscardSettings()">Cancel</button>
    </div>
  </div>

  <!-- ══════════════════ PRIVACY ══════════════════ -->
  <div class="screen" id="s-privacy">
    <div class="hdr"><div class="hdr-row"><button class="back" onclick="back()"><i class="ti ti-arrow-left"></i></button><span class="hdr-title">Privacy & security</span></div></div>
    <div class="scroll" style="padding:16px">
      <div style="font-size:13px;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.6px;margin-bottom:10px">Password</div>
      <div class="fg"><label class="fl">Current password</label><input class="fi" type="password" placeholder="••••••••"></div>
      <div class="fg"><label class="fl">New password</label><input class="fi" id="new-pw" type="password" placeholder="At least 8 characters"><div class="prog-bar"><div class="prog-fill" id="pw-strength" style="width:0%;background:var(--red)"></div></div><div style="font-size:11px;color:var(--muted);margin-top:4px" id="pw-hint">Enter a new password</div></div>
      <div class="fg"><label class="fl">Confirm new password</label><input class="fi" type="password" placeholder="Repeat new password"></div>
      <div style="font-size:13px;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.6px;margin:16px 0 10px">Security</div>
      <div style="display:flex;align-items:center;justify-content:space-between;padding:12px 0;border-bottom:.5px solid var(--border)">
        <div><div style="font-size:14px;font-weight:600;color:var(--txt)">Two-factor authentication</div><div style="font-size:12px;color:var(--muted);margin-top:2px">SMS verification on login</div></div>
        <label style="position:relative;display:inline-block;width:44px;height:24px;cursor:pointer"><input type="checkbox" id="tfa-tog" style="opacity:0;width:0;height:0" onchange="showToast(this.checked?'2FA enabled':'2FA disabled')"><span style="position:absolute;inset:0;background:var(--bg3);border-radius:12px;transition:background .2s;border:.5px solid var(--border)" id="tfa-track"></span><span id="tfa-thumb" style="position:absolute;left:3px;top:3px;width:18px;height:18px;border-radius:50%;background:#fff;transition:transform .2s;box-shadow:0 1px 4px rgba(0,0,0,.2)"></span></label>
      </div>
      <button class="btn btn-g" style="margin-top:20px" onclick="showToast('Settings saved ✓')"><i class="ti ti-device-floppy"></i> Save changes</button>
    </div>
  </div>

  <!-- ══════════════════ NAV ══════════════════ -->
  <div class="nav">
    <button class="nitem active" id="nav-home" onclick="go('home')" aria-label="Home"><i class="ti ti-home"></i><span>Home</span></button>
    <button class="nitem" id="nav-search" onclick="go('search')" aria-label="Search"><i class="ti ti-search"></i><span>Search</span></button>
    <button class="nitem" id="nav-sell" onclick="isGuest?requireAuth('Sign in to sell','Create an account to list items on the marketplace.'):go('sell')" aria-label="Sell">
      <div class="sell-fab"><i class="ti ti-plus"></i></div>
      <span>Sell</span>
    </button>
    <button class="nitem" id="nav-bulletin" onclick="go('bulletin')" aria-label="Bulletin"><i class="ti ti-message-circle"></i><span>Bulletin</span></button>
    <button class="nitem" id="nav-profile" onclick="go('profile')" aria-label="Profile"><i class="ti ti-user"></i><span>Profile</span></button>
  </div>

  <!-- ══════════════════ MODALS ══════════════════ -->
  <!-- Filter Modal -->
  <div class="modal-bg" id="filter-modal" onclick="if(event.target===this)closeModal('filter-modal')">
    <div class="modal">
      <div class="mhdr"><h3>Filter & sort</h3><button class="close-m" onclick="closeModal('filter-modal')"><i class="ti ti-x"></i></button></div>
      <div class="mbody">
        <div class="fg"><label class="fl">Sort by</label>
          <select class="fsel" id="f-sort" onchange="applyFilters()">
            <option value="newest">Newest first</option><option value="price-asc">Price: low to high</option>
            <option value="price-desc">Price: high to low</option><option value="rating">Top rated</option>
          </select>
        </div>
        <div class="fg"><label class="fl">Max price: R <span id="f-price-val">500</span></label>
          <div class="frange"><span style="font-size:12px;color:var(--muted)">R 0</span><input type="range" min="0" max="1000" step="10" value="500" id="f-price" oninput="document.getElementById('f-price-val').textContent=this.value;applyFilters()"><span style="font-size:12px;color:var(--muted)">R 1000</span></div>
        </div>
        <div class="fg"><label class="fl">Condition</label>
          <div style="display:flex;flex-wrap:wrap;gap:8px">
            <button class="chip active" data-cond="All" onclick="condChip(this)">All</button>
            <button class="chip" data-cond="New" onclick="condChip(this)">New</button>
            <button class="chip" data-cond="Used – Like new" onclick="condChip(this)">Like new</button>
            <button class="chip" data-cond="Used – Good" onclick="condChip(this)">Good</button>
            <button class="chip" data-cond="Used – Fair" onclick="condChip(this)">Fair</button>
          </div>
        </div>
        <button class="btn btn-g" onclick="applyFilters();closeModal('filter-modal');showToast('Filters applied')">Apply filters</button>
        <button class="btn btn-s" onclick="resetFilters()">Reset</button>
      </div>
    </div>
  </div>

  <!-- Message Seller Modal -->
  <div class="modal-bg" id="msg-modal" onclick="if(event.target===this)closeModal('msg-modal')">
    <div class="modal">
      <div class="mhdr"><h3>Message seller</h3><button class="close-m" onclick="closeModal('msg-modal')"><i class="ti ti-x"></i></button></div>
      <div class="mbody">
        <div style="display:flex;align-items:center;gap:10px;margin-bottom:14px;padding:12px;background:var(--bg2);border-radius:var(--rlg)">
          <div class="ava" id="msg-ava" style="background:var(--gl);color:var(--gd);width:36px;height:36px;font-size:12px"></div>
          <div><div style="font-size:13px;font-weight:700;color:var(--txt)" id="msg-seller-name">Seller</div><div style="font-size:11px;color:var(--muted)">Usually replies within 2 hours</div></div>
        </div>
        <div class="fg"><label class="fl">Your message *</label><textarea class="fta" id="msg-text" rows="4" placeholder="Hi, is this still available? I'm interested in…"></textarea><span class="err-msg">Please write a message</span></div>
        <div class="fg"><label class="fl">Your name</label><input class="fi" id="msg-name" type="text" placeholder="Your name"></div>
        <button class="btn btn-g" onclick="sendMessage()"><i class="ti ti-send"></i> Send message</button>
      </div>
    </div>
  </div>

  <!-- Review Modal -->
  <div class="modal-bg" id="review-modal" onclick="if(event.target===this)closeModal('review-modal')">
    <div class="modal">
      <div class="mhdr"><h3>Leave a review</h3><button class="close-m" onclick="closeModal('review-modal')"><i class="ti ti-x"></i></button></div>
      <div class="mbody">
        <div class="fg"><label class="fl">Star rating *</label>
          <div class="star-input" id="star-input">
            <button onclick="setStars(1)">★</button><button onclick="setStars(2)">★</button>
            <button onclick="setStars(3)">★</button><button onclick="setStars(4)">★</button>
            <button onclick="setStars(5)">★</button>
          </div>
        </div>
        <div class="fg"><label class="fl">Review *</label><textarea class="fta" id="rev-text" rows="3" placeholder="Share your experience with this seller…"></textarea></div>
        <div class="fg"><label class="fl">Your name</label><input class="fi" id="rev-name" type="text" placeholder="First name or initials"></div>
        <button class="btn btn-g" onclick="submitReview()"><i class="ti ti-star"></i> Submit review</button>
      </div>
    </div>
  </div>

  <!-- Confirmation Modal -->
  <div class="modal-bg" id="confirm-modal" onclick="if(event.target===this)closeModal('confirm-modal')">
    <div class="modal">
      <div class="mhdr"><h3 id="confirm-title">Are you sure?</h3><button class="close-m" onclick="closeModal('confirm-modal')"><i class="ti ti-x"></i></button></div>
      <div class="mbody">
        <p style="font-size:13.5px;color:var(--muted);line-height:1.6;margin-bottom:18px" id="confirm-msg">This action cannot be undone.</p>
        <button class="btn btn-g" id="confirm-btn-action" onclick="runConfirm()">Confirm</button>
        <button class="btn btn-s" onclick="closeModal('confirm-modal')">Cancel</button>
      </div>
    </div>
  </div>

  <!-- Guest Gate Modal -->
  <div class="modal-bg" id="guest-gate-modal" onclick="if(event.target===this)closeModal('guest-gate-modal')">
    <div class="guest-gate-modal">
      <div class="guest-gate-icon">🔒</div>
      <h3 id="gate-title">Sign in required</h3>
      <p id="gate-msg">You need an account to do this. Sign up or sign in to continue — it only takes a moment!</p>
      <button class="btn btn-g" onclick="closeModal('guest-gate-modal');signOut()"><i class="ti ti-login-2"></i> Sign in or create account</button>
      <button class="btn btn-s" style="margin-top:8px" onclick="closeModal('guest-gate-modal')">Maybe later</button>
    </div>
  </div>

  <!-- Payment Processing Overlay -->
  <div class="pay-processing" id="pay-processing">
    <div class="pay-spinner"></div>
    <div class="pay-status" id="pay-status-text">Processing payment…</div>
    <div class="pay-sub" id="pay-sub-text">Please wait, do not close this screen</div>
  </div>

  <!-- Hidden file inputs -->
  <input type="file" id="photo-input" accept="image/*" style="display:none" onchange="handlePhotoUpload(event)">
  <input type="file" id="avatar-input" accept="image/*" style="display:none" onchange="handleAvatarUpload(event)">

  <div class="toast" id="toast" role="status" aria-live="polite"></div>
</div>

<script>
// ══════════════════════════════════════════
//  DATA
// ══════════════════════════════════════════
const PRODUCTS = [
  {id:'calc',  emoji:'🧮', bg:'var(--gl)',   price:180,   priceDisp:'R 180',   title:'Scientific Calculator (Casio FX-991ZA)', stars:5, reviews:12, seller:'Sipho Mokoena',   avaText:'SM', avaBg:'var(--gl)',  avaC:'var(--gd)',  category:'Electronics', condition:'Used – Good',     desc:'Casio FX-991ZA Plus. Works perfectly, used one semester. Comes with cover. Selling because I graduated. Ideal for engineering & science students.'},
  {id:'book',  emoji:'📘', bg:'var(--bl)',   price:350,   priceDisp:'R 350',   title:'Project Management Textbook, 3rd Ed.',    stars:4, reviews:8,  seller:'Nomsa Khumalo',   avaText:'NK', avaBg:'var(--bl)',  avaC:'var(--bc)',  category:'Books',       condition:'Used – Good',     desc:'Kloppenborg, Anantatmula & Wells — Contemporary Project Management 3rd Ed. Slight highlighting in ch 3–5. Perfect for PRM370/371/372S.'},
  {id:'food',  emoji:'🍱', bg:'var(--ol)',   price:55,    priceDisp:'R 55',    title:'Campus Lunch Box (Daily Order)',           stars:5, reviews:34, seller:'Mama Thandi',     avaText:'MT', avaBg:'var(--ol)',  avaC:'var(--oc)',  category:'Food',        condition:'New daily',       desc:'Fresh home-cooked meals, 3-course. Order by 09:00 for 12:30 campus gate delivery. Pap & vleis, rice dishes, salads. Vegetarian available.'},
  {id:'laptop',emoji:'💻', bg:'var(--pl)',   price:220,   priceDisp:'R 220',   title:'Adjustable Laptop Stand (Aluminium)',      stars:4, reviews:5,  seller:'TechHub Store',   avaText:'TH', avaBg:'var(--pl)',  avaC:'var(--pc)',  category:'Electronics', condition:'Used – Like new',  desc:'Foldable aluminium stand with 6 height levels. Fits 11–17" laptops. Reduces neck strain. Barely used, in original box with manual.'},
  {id:'hoodie',emoji:'👕', bg:'var(--pink)', price:150,   priceDisp:'R 150',   title:'TUT Hoodie — Size Medium',                stars:4, reviews:3,  seller:'Lerato D.',       avaText:'LD', avaBg:'var(--pink)',avaC:'var(--pinkc)',category:'Clothing',    condition:'Used – Good',     desc:'Official TUT hoodie, medium. Navy blue. Gently washed, no fading. Worn only a few times. Great for cold campus mornings.'},
  {id:'tut',   emoji:'📝', bg:'var(--bg2)',  price:80,    priceDisp:'R 80/hr', title:'Maths 2B Tutoring (Online or On-Campus)', stars:5, reviews:7,  seller:'Kgosi Nkosi',    avaText:'KN', avaBg:'var(--bg3)',avaC:'var(--txt)', category:'Services',    condition:'Service',         desc:'3rd-year engineering student offering Maths 2B tutoring. Passed with distinction. Weekends and evenings available. Flexible location.'},
];

const BULLETIN_POSTS = [
  {tag:'Event',     tagClass:'t-ev', title:'Campus Sustainability Market — Sat 28 June', meta:'Student Union · 2 hours ago · 47 interested'},
  {tag:'For sale',  tagClass:'t-sa', title:'Final-year engineering textbook bundle (6 books) — R 800', meta:'Keitumetse D. · 5 hours ago · 12 views'},
  {tag:'Service',   tagClass:'t-sv', title:'Freelance graphic design — logos, posters, CV templates', meta:'Amahle Studio · Yesterday · ★★★★★'},
  {tag:'Lost & found',tagClass:'t-lo',title:'Lost: Black TUT hoodie, Library Block B, Tuesday', meta:'Lethabo M. · 2 days ago'},
  {tag:'Event',     tagClass:'t-ev', title:'Drama Society bake sale — proceeds to costumes fund', meta:'Drama Soc · 3 days ago · 88 views'},
];

const REVIEWS_DATA = [
  {ava:'NK', avaBg:'var(--bl)', avaC:'var(--bc)', name:'Nomsa K.',  stars:5, text:'Fast pickup, item exactly as described. Would definitely buy again!', time:'2 days ago'},
  {ava:'TM', avaBg:'var(--pl)', avaC:'var(--pc)', name:'Thabo M.',  stars:5, text:'Reliable seller. Laptop stand in great condition. Highly recommend.', time:'1 week ago'},
  {ava:'LD', avaBg:'var(--ol)', avaC:'var(--oc)', name:'Lerato D.', stars:4, text:'Good communication. Item had minor wear not mentioned, but price was fair.', time:'2 weeks ago'},
];

const NOTIFICATIONS_DATA = [
  {title:'Order confirmed', body:'Sipho Mokoena confirmed your calculator order. Collect at Building 5 tomorrow 10:00–14:00.', time:'2 hours ago', unread:true, target:{screen:'orders'}},
  {title:'New listing in Books', body:'A PM textbook (3rd Ed.) listed nearby for R 300. Check it out!', time:'5 hours ago', unread:true, target:{screen:'search', cat:'Books'}},
  {title:'You received a 5-star review', body:'Thabo M.: "Reliable seller. Highly recommend."', time:'2 days ago', unread:false, target:{screen:'ratings'}},
  {title:'Campus Sustainability Market', body:'Reminder: this Saturday at Engineering Building forecourt. 47 students interested.', time:'3 days ago', unread:false, target:{screen:'bulletin'}},
];

const ORDERS_DATA = [
  {emoji:'🧮', title:'Scientific Calculator', price:'R 183.60', status:'Confirmed', statusClass:'s-conf', date:'25 Jun 2026'},
  {emoji:'📘', title:'PM Textbook 3rd Ed.', price:'R 357.00', status:'Completed', statusClass:'s-comp', date:'10 Jun 2026'},
  {emoji:'🍱', title:'Campus Lunch Box', price:'R 56.10', status:'Pending', statusClass:'s-pend', date:'24 Jun 2026'},
];

// ══════════════════════════════════════════
//  STATE
// ══════════════════════════════════════════
let history = ['landing'];
const cartItems = []; // {product, qty}
const wishlist = new Set();
let currentProductId = null;
let currentPhotoSlot = 0;
let filterCat = 'All';
let searchFilterCat = 'All';
let selectedStars = 0;
let filterSort = 'newest';
let filterMaxPrice = 1000;
let filterCond = 'All';
let notifications = [...NOTIFICATIONS_DATA];
let bulletinPosts = [...BULLETIN_POSTS];
let reviews = [...REVIEWS_DATA];
let profileData = {name:'Precious Mokoena', email:'precious@tut.ac.za', phone:'', campus:'', avatarSrc:null};
const uploadedProductPhotos = [null,null,null,null,null]; // per slot DataURLs

// ══════════════════════════════════════════
//  NAV
// ══════════════════════════════════════════
const NAV_KEYS = ['home','search','sell','bulletin','profile'];
function go(id) {
  // Guest gating: block access to transactional screens
  if (isGuest && GATED_SCREENS.includes(id)) {
    const msgs = {
      cart: ['Sign in to view your cart', 'Add items and check out securely with your campus account.'],
      checkout: ['Sign in to checkout', 'Complete your purchase safely with a verified campus account.'],
      sell: ['Sign in to sell', 'Create an account to list your items on the campus marketplace.'],
      'post-bulletin': ['Sign in to post', 'Sign in to post announcements on the bulletin board.'],
      orders: ['Sign in to view orders', 'Track your purchases and order history with an account.'],
      wishlist: ['Sign in to use wishlist', 'Save items you love and come back to them anytime.'],
      notifications: ['Sign in for notifications', 'Get updates on your listings, orders, and messages.'],
      'account-settings': ['Sign in required', 'Manage your profile with a campus account.'],
      privacy: ['Sign in required', 'Access your privacy and security settings.'],
    };
    const [title, msg] = msgs[id] || ['Sign in required', 'Create a free account or sign in to continue.'];
    requireAuth(title, msg);
    return;
  }
  document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
  const el = document.getElementById('s-'+id);
  if (!el) return;
  el.classList.add('active');
  history.push(id);
  document.querySelector('.nav').style.display = (id==='landing'||id==='auth') ? 'none' : 'flex';
  updateNav(id);
  onEnter(id);
}
function back() {
  if (history.length > 1) history.pop();
  const prev = history[history.length-1] || 'home';
  history.pop();
  go(prev);
}
function updateNav(id) {
  document.querySelectorAll('.nitem').forEach(n=>n.classList.remove('active'));
  const key = NAV_KEYS.includes(id) ? id : [...history].reverse().find(s=>NAV_KEYS.includes(s)) || 'home';
  const el = document.getElementById('nav-'+key);
  if (el) el.classList.add('active');
}
function onEnter(id) {
  if (id==='home') renderHomeGrids();
  if (id==='bulletin') renderBulletin();
  if (id==='ratings') renderReviews();
  if (id==='notifications') renderNotifications();
  if (id==='orders') renderOrders();
  if (id==='wishlist') renderWishlist();
  if (id==='cart') renderCart();
  if (id==='checkout') renderCheckout();
  if (id==='account-settings') loadAccountSettings();
  if (id==='search') { setTimeout(()=>document.getElementById('main-search').focus(),100); }
}

// ══════════════════════════════════════════
//  RENDER HOME
// ══════════════════════════════════════════
function renderHomeGrids() {
  const featured = PRODUCTS.filter(p=>filterCat==='All'||p.category===filterCat).slice(0,4);
  const nearby = PRODUCTS.filter(p=>filterCat==='All'||p.category===filterCat).slice(2,6);
  document.getElementById('home-grid').innerHTML  = featured.map(p=>productCard(p,'home-grid')).join('');
  document.getElementById('home-grid2').innerHTML = nearby.map(p=>productCard(p,'home-grid2')).join('');
  document.getElementById('home-username').textContent = profileData.name.split(' ')[0];
}
function homeFilter(btn, cat) {
  document.querySelectorAll('#home-chips .chip').forEach(c=>c.classList.remove('active'));
  btn.classList.add('active');
  filterCat = cat;
  renderHomeGrids();
}

// ══════════════════════════════════════════
//  PRODUCT CARD
// ══════════════════════════════════════════
function productCard(p) {
  const wishedClass = wishlist.has(p.id) ? 'active' : '';
  const wishedIcon  = wishlist.has(p.id) ? 'ti-heart-filled' : 'ti-heart';
  const stars = '★'.repeat(p.stars) + '☆'.repeat(5-p.stars);
  const imgHtml = p.uploadedImg
    ? `<img src="${p.uploadedImg}" style="width:100%;height:100%;object-fit:cover;position:absolute;inset:0" alt="${p.title}">`
    : `<span>${p.emoji}</span>`;
  return `<div class="pcard" onclick="showProduct('${p.id}')">
    <div class="pimg" style="background:${p.bg}">${imgHtml}
      <button class="pwish ${wishedClass}" onclick="event.stopPropagation();toggleWishlist('${p.id}')" aria-label="Wishlist"><i class="ti ${wishedIcon}"></i></button>
    </div>
    <div class="pinfo">
      <div class="pname">${p.title}</div>
      <div class="pprice">${p.priceDisp}</div>
      <div class="pseller">by ${p.seller}</div>
      <div class="pstars">${stars} (${p.reviews})</div>
    </div>
  </div>`;
}

// ══════════════════════════════════════════
//  PRODUCT DETAIL
// ══════════════════════════════════════════
function showProduct(id) {
  const p = PRODUCTS.find(x=>x.id===id);
  if (!p) return;
  currentProductId = id;
  document.getElementById('d-htitle').textContent = 'Product';
  // image
  const uploaded = document.getElementById('d-img-uploaded');
  const emoji    = document.getElementById('d-emoji');
  if (p.uploadedImg) {
    uploaded.src = p.uploadedImg; uploaded.style.display='block'; emoji.style.display='none';
  } else {
    emoji.textContent=p.emoji; emoji.style.display='block'; uploaded.style.display='none';
  }
  document.getElementById('d-img-bg').style.background = p.bg;
  document.getElementById('d-price').textContent = p.priceDisp;
  document.getElementById('d-title').textContent = p.title;
  const stars = '★'.repeat(p.stars)+'☆'.repeat(5-p.stars);
  document.getElementById('d-stars').textContent = stars+` (${p.reviews} reviews)`;
  document.getElementById('d-cond').textContent = p.condition;
  document.getElementById('d-seller').textContent = p.seller;
  document.getElementById('d-seller-sub').textContent = `Student vendor · ${p.reviews*3} listings`;
  document.getElementById('d-ava-txt').textContent = p.avaText;
  document.getElementById('d-ava').style.background = p.avaBg;
  document.getElementById('d-ava').style.color = p.avaC;
  // seller avatar uploaded?
  const avaImg = document.getElementById('d-ava-img');
  if (profileData.avatarSrc && p.seller===profileData.name) {
    avaImg.src=profileData.avatarSrc; avaImg.style.display='block';
    document.getElementById('d-ava-txt').style.display='none';
  } else { avaImg.style.display='none'; document.getElementById('d-ava-txt').style.display='block'; }
  document.getElementById('d-desc').textContent = p.desc;
  updateWishlistBtn();
  document.getElementById('msg-ava').textContent = p.avaText;
  document.getElementById('msg-ava').style.background = p.avaBg;
  document.getElementById('msg-ava').style.color = p.avaC;
  document.getElementById('msg-seller-name').textContent = p.seller;
  go('product');
}

function updateWishlistBtn() {
  if (!currentProductId) return;
  const wished = wishlist.has(currentProductId);
  document.getElementById('d-wish-btn').querySelector('i').className = wished ? 'ti ti-heart-filled' : 'ti ti-heart';
  document.getElementById('d-wish-icon').className = wished ? 'ti ti-heart-filled' : 'ti ti-heart';
  document.getElementById('d-wish-lbl').textContent = wished ? 'Remove from wishlist' : 'Save to wishlist';
}
function toggleWishlist(id) {
  if (!requireAuth('Sign in to use wishlist', 'Save items you love and come back to them anytime.')) return;
  if (wishlist.has(id)) { wishlist.delete(id); showToast('Removed from wishlist'); }
  else { wishlist.add(id); showToast('Saved to wishlist ♡'); }
  renderHomeGrids();
  if (document.getElementById('s-search').classList.contains('active')) renderSearchResults();
  updateWishlistBadge();
  if (currentProductId===id) updateWishlistBtn();
}
function toggleWishlistCurrent() { if (currentProductId) toggleWishlist(currentProductId); }
function updateWishlistBadge() {
  const c = wishlist.size;
  const badge = document.getElementById('wish-count-badge');
  badge.textContent = c; badge.style.display = c>0 ? 'inline' : 'none';
}

// ══════════════════════════════════════════
//  CART
// ══════════════════════════════════════════
function addToCart() {
  if (!requireAuth('Sign in to add to cart', 'Create an account to shop and checkout securely on campus.')) return;
  const p = PRODUCTS.find(x=>x.id===currentProductId);
  if (!p) return;
  const existing = cartItems.find(x=>x.id===p.id);
  if (existing) existing.qty++;
  else cartItems.push({...p, qty:1});
  updateCartHeader();
}
function updateCartHeader() {
  const total = cartItems.reduce((s,x)=>s+x.qty,0);
  document.getElementById('cart-sub-hdr').textContent = total+' item'+(total!==1?'s':'');
}
function renderCart() {
  const empty = cartItems.length===0;
  document.getElementById('cart-empty').style.display = empty?'flex':'none';
  document.getElementById('cart-has').style.display   = empty?'none':'flex';
  if (empty) return;
  document.getElementById('cart-items-list').innerHTML = cartItems.map((item,i)=>{
    const imgHtml = item.uploadedImg
      ? `<img src="${item.uploadedImg}" style="width:100%;height:100%;object-fit:cover" alt="${item.title}">`
      : item.emoji;
    return `<div class="citem">
      <div class="cemoji" style="background:${item.bg};font-size:${item.uploadedImg?'0':'32px'}">${imgHtml}</div>
      <div style="flex:1">
        <div class="cname">${item.title}</div>
        <div class="cprice">R ${(item.price*item.qty).toFixed(2)}</div>
        <div class="qrow">
          <button class="qbtn" onclick="adjustQty(${i},-1)">−</button>
          <span class="qnum">${item.qty}</span>
          <button class="qbtn" onclick="adjustQty(${i},1)">+</button>
        </div>
      </div>
      <button class="trsh" onclick="confirmRemoveCartItem(${i})" aria-label="Remove"><i class="ti ti-trash"></i></button>
    </div>`;
  }).join('');
  renderCartSummary('cart-summary');
  updateCartHeader();
}
function adjustQty(i,d) {
  cartItems[i].qty = Math.max(1, cartItems[i].qty+d);
  renderCart();
}
function removeCartItem(i) {
  cartItems.splice(i,1); renderCart(); showToast('Item removed');
}
function confirmRemoveCartItem(i) {
  const item = cartItems[i];
  if (!item) return;
  showConfirm('Remove item?', `Remove "${item.title}" from your cart?`, 'Remove', ()=>removeCartItem(i), true);
}
function clearCart() {
  cartItems.length=0; renderCart(); updateCartHeader();
}
function cartTotal() {
  return cartItems.reduce((s,x)=>s+x.price*x.qty,0);
}
function renderCartSummary(elId) {
  const sub   = cartTotal();
  const fee   = sub*0.02;
  const total = sub+fee;
  document.getElementById(elId).innerHTML = `
    <div class="srow"><span>Subtotal</span><span>R ${sub.toFixed(2)}</span></div>
    <div class="srow"><span>Platform fee (2%)</span><span>R ${fee.toFixed(2)}</span></div>
    <div class="srow"><span>Campus pickup</span><span style="color:var(--g);font-weight:700">Free</span></div>
    <div class="srow tot"><span>Total</span><span>R ${total.toFixed(2)}</span></div>`;
}
function renderCheckout() {
  renderCartSummary('co-summary');
  const t = (cartTotal()*1.02).toFixed(2);
  document.getElementById('co-total-btn').textContent = 'R '+t;
}
function confirmAndPay() {
  if (!requireAuth('Sign in to pay', 'You need an account to make payments.')) return;
  if (cartItems.length===0) { showToast('Your cart is empty'); return; }

  // Determine selected payment method
  const pmNames = {payfast:'PayFast (Card / EFT)',snapscan:'SnapScan',escrow:'Escrow'};
  const selPmEl = document.querySelector('.pchoice-card.sel');
  const pmId = selPmEl ? selPmEl.id.replace('pm-','') : 'payfast';
  const pmName = pmNames[pmId] || 'PayFast';

  // Show processing overlay
  const proc = document.getElementById('pay-processing');
  const statusEl = document.getElementById('pay-status-text');
  const subEl = document.getElementById('pay-sub-text');
  proc.classList.add('show');

  const steps = [
    {status:'Connecting to '+pmName+'…', sub:'Securing your connection'},
    {status:'Verifying payment details…', sub:'Almost there'},
    {status:'Confirming with seller…', sub:'Payment approved ✓'},
  ];
  let step = 0;
  function nextStep() {
    if (step < steps.length) {
      statusEl.textContent = steps[step].status;
      subEl.textContent = steps[step].sub;
      step++;
      setTimeout(nextStep, 900);
    } else {
      proc.classList.remove('show');
      showSuccessScreen(pmName);
    }
  }
  statusEl.textContent = 'Processing payment…';
  subEl.textContent = 'Please wait, do not close this screen';
  setTimeout(nextStep, 700);
}

function showSuccessScreen(pmName) {
  const item = cartItems[0];
  const subtotal = cartTotal();
  const fee = subtotal * 0.02;
  const total = subtotal + fee;
  const orderNum = 'CS-2026-' + Date.now().toString().slice(-5);

  // Update receipt
  document.getElementById('success-order-num').textContent = 'Order #' + orderNum;
  document.getElementById('success-msg').textContent = `Payment of R ${total.toFixed(2)} confirmed via ${pmName}. The seller will reach out within 24 hours to arrange pickup.`;

  document.getElementById('receipt-items').innerHTML = cartItems.map(ci => `
    <div class="receipt-row">
      <span class="rl">${ci.emoji || ''} ${ci.title}${ci.qty > 1 ? ' × ' + ci.qty : ''}</span>
      <span class="rv">R ${(ci.price * ci.qty).toFixed(2)}</span>
    </div>`).join('');

  document.getElementById('receipt-sub').textContent = 'R ' + subtotal.toFixed(2);
  document.getElementById('receipt-fee').textContent = 'R ' + fee.toFixed(2);
  document.getElementById('receipt-total').textContent = 'R ' + total.toFixed(2);

  // Add to orders
  ORDERS_DATA.unshift({
    emoji: item.emoji,
    title: cartItems.length > 1 ? `${item.title} +${cartItems.length - 1} more` : item.title,
    price: 'R ' + total.toFixed(2),
    status: 'Pending',
    statusClass: 's-pend',
    date: new Date().toLocaleDateString('en-ZA', {day:'numeric', month:'short', year:'numeric'})
  });
  document.getElementById('stat-orders').textContent = parseInt(document.getElementById('stat-orders').textContent) + 1;

  // Add notification
  notifications.unshift({
    title: 'Order placed — #' + orderNum,
    body: `R ${total.toFixed(2)} paid via ${pmName}. Collect at Building 5, Student Hub.`,
    time: 'Just now',
    unread: true,
    target: {screen:'orders'}
  });
  updateNotifDot();

  go('success');
  // Trigger confetti after screen is visible
  setTimeout(launchConfetti, 200);
}

function launchConfetti() {
  const canvas = document.getElementById('confetti-canvas');
  if (!canvas) return;
  const ctx = canvas.getContext('2d');
  canvas.width = canvas.offsetWidth;
  canvas.height = canvas.offsetHeight;

  const colours = ['#1D9E75','#EF9F27','#3C3489','#E24B4A','#fff','#185FA5'];
  const pieces = Array.from({length:90}, () => ({
    x: Math.random() * canvas.width,
    y: -10 - Math.random() * 80,
    r: 4 + Math.random() * 6,
    d: 1.5 + Math.random() * 2.5,
    color: colours[Math.floor(Math.random() * colours.length)],
    tilt: Math.random() * 10 - 5,
    tiltAngle: 0,
    tiltSpeed: 0.05 + Math.random() * 0.1,
  }));

  let frame = 0;
  function draw() {
    if (frame > 220) { ctx.clearRect(0,0,canvas.width,canvas.height); return; }
    ctx.clearRect(0,0,canvas.width,canvas.height);
    pieces.forEach(p => {
      p.tiltAngle += p.tiltSpeed;
      p.y += p.d;
      p.x += Math.sin(p.tiltAngle) * 1.2;
      p.tilt = Math.sin(p.tiltAngle) * 10;
      ctx.beginPath();
      ctx.lineWidth = p.r;
      ctx.strokeStyle = p.color;
      ctx.moveTo(p.x + p.tilt + p.r/4, p.y);
      ctx.lineTo(p.x + p.tilt, p.y + p.tilt + p.r/4);
      ctx.stroke();
    });
    frame++;
    requestAnimationFrame(draw);
  }
  draw();
}
function selPM(id) {
  ['payfast','snapscan','escrow'].forEach(pm=>{
    document.getElementById('pm-'+pm).classList.remove('sel');
  });
  document.getElementById('pm-'+id).classList.add('sel');
  const names={payfast:'PayFast',snapscan:'SnapScan',escrow:'Escrow'};
  showToast(names[id]+' selected');
}

// ══════════════════════════════════════════
//  SEARCH
// ══════════════════════════════════════════
let searchQuery = '';
function doSearch(q) {
  searchQuery = q.trim().toLowerCase();
  document.getElementById('search-trending').style.display = q ? 'none':'block';
  document.getElementById('search-results').style.display  = q ? 'block':'none';
  renderSearchResults();
}
function setSearch(q) {
  document.getElementById('main-search').value = q;
  doSearch(q);
}
function clearSearch() {
  document.getElementById('main-search').value='';
  doSearch('');
}
function searchFilter(btn,cat) {
  document.querySelectorAll('#search-chips .chip').forEach(c=>c.classList.remove('active'));
  btn.classList.add('active');
  searchFilterCat = cat;
  if (searchQuery) renderSearchResults();
}
function renderSearchResults() {
  let results = PRODUCTS.filter(p=>{
    const matchQ = !searchQuery || p.title.toLowerCase().includes(searchQuery) || p.category.toLowerCase().includes(searchQuery) || p.seller.toLowerCase().includes(searchQuery) || p.desc.toLowerCase().includes(searchQuery);
    const matchC = searchFilterCat==='All' || p.category===searchFilterCat;
    const matchP = p.price <= filterMaxPrice;
    const matchCond = filterCond==='All' || p.condition===filterCond;
    return matchQ && matchC && matchP && matchCond;
  });
  if (filterSort==='price-asc')  results.sort((a,b)=>a.price-b.price);
  if (filterSort==='price-desc') results.sort((a,b)=>b.price-a.price);
  if (filterSort==='rating')     results.sort((a,b)=>b.stars-a.stars);
  document.getElementById('result-count').textContent = results.length+' listing'+(results.length!==1?'s':'');
  document.getElementById('result-grid').innerHTML = results.map(p=>productCard(p)).join('');
  document.getElementById('no-results').style.display = results.length ? 'none':'block';
  document.getElementById('result-grid').style.display = results.length ? 'grid':'none';
}
function applyFilters() {
  filterSort     = document.getElementById('f-sort').value;
  filterMaxPrice = parseInt(document.getElementById('f-price').value);
  if (searchQuery) renderSearchResults();
}
function condChip(btn) {
  btn.closest('.fg').querySelectorAll('.chip').forEach(c=>c.classList.remove('active'));
  btn.classList.add('active');
  filterCond = btn.dataset.cond;
  applyFilters();
}
function resetFilters() {
  filterSort='newest'; filterMaxPrice=1000; filterCond='All';
  document.getElementById('f-sort').value='newest';
  document.getElementById('f-price').value=1000;
  document.getElementById('f-price-val').textContent='1000';
  document.querySelectorAll('#filter-modal .chip').forEach(c=>c.classList.remove('active'));
  document.querySelector('#filter-modal [data-cond="All"]').classList.add('active');
  if (searchQuery) renderSearchResults();
  showToast('Filters reset');
}

// ══════════════════════════════════════════
//  BULLETIN
// ══════════════════════════════════════════
let bullFilterCat = 'All';
function renderBulletin() {
  const list = bulletinPosts.filter(b=>bullFilterCat==='All'||b.tag===bullFilterCat);
  document.getElementById('bull-list').innerHTML = list.map(b=>`
    <div class="bcard" onclick="showToast('Opening: ${b.title.substring(0,30)}…')">
      <span class="btag ${b.tagClass}">${b.tag}</span>
      <div class="btitle">${b.title}</div>
      <div class="bmeta">${b.meta}</div>
    </div>`).join('') + (list.length===0?'<div class="no-results"><i class="ti ti-mood-empty"></i><p>No posts in this category yet.</p></div>':'');
}
function bullFilter(btn,cat) {
  document.querySelectorAll('#bull-chips .chip').forEach(c=>c.classList.remove('active'));
  btn.classList.add('active');
  bullFilterCat = cat;
  renderBulletin();
}
function validate(id) {
  const el = document.getElementById(id);
  const empty = !el.value.trim();
  el.classList.toggle('err', empty);
  return !empty;
}
function submitBulletin() {
  const okCat   = validate('pb-cat');
  const okTitle = validate('pb-title');
  const okDet   = validate('pb-details');
  if (!okCat||!okTitle||!okDet) { showToast('Please fill in required fields'); return; }
  const tagMap = {'Event':'t-ev','For sale':'t-sa','Service':'t-sv','Lost & found':'t-lo','Fundraiser':'t-ev'};
  const cat = document.getElementById('pb-cat').value;
  bulletinPosts.unshift({
    tag: cat, tagClass: tagMap[cat]||'t-sv',
    title: document.getElementById('pb-title').value.trim(),
    meta: `You · Just now · ${document.getElementById('pb-contact').value||'No contact given'}`
  });
  ['pb-cat','pb-title','pb-details','pb-contact'].forEach(id=>{
    const el=document.getElementById(id); el.value=''; el.classList.remove('err');
  });
  showToast('Announcement posted ✓');
  back();
}

// ══════════════════════════════════════════
//  RATINGS & REVIEWS
// ══════════════════════════════════════════
function renderReviews() {
  document.getElementById('reviews-list').innerHTML = reviews.map(r=>`
    <div class="ritem">
      <div class="rrow">
        <div class="ava" style="background:${r.avaBg};color:${r.avaC};width:36px;height:36px;font-size:12px">${r.ava}</div>
        <div><div style="font-size:13px;font-weight:700;color:var(--txt)">${r.name}</div><div style="color:var(--amber);font-size:12px">${'★'.repeat(r.stars)+'☆'.repeat(5-r.stars)}</div></div>
        <div style="margin-left:auto;font-size:11px;color:var(--muted)">${r.time}</div>
      </div>
      <div class="rtxt">${r.text}</div>
    </div>`).join('');
}
function setStars(n) {
  selectedStars = n;
  document.querySelectorAll('#star-input button').forEach((btn,i)=>btn.classList.toggle('lit',i<n));
}
function submitReview() {
  const text = document.getElementById('rev-text').value.trim();
  const name = document.getElementById('rev-name').value.trim()||'Anonymous';
  if (!selectedStars) { showToast('Please select a star rating'); return; }
  if (!text) { document.getElementById('rev-text').classList.add('err'); showToast('Please write a review'); return; }
  reviews.unshift({ava:name.slice(0,2).toUpperCase(), avaBg:'var(--gl)', avaC:'var(--gd)', name, stars:selectedStars, text, time:'Just now'});
  renderReviews();
  document.getElementById('rev-text').value='';
  document.getElementById('rev-name').value='';
  document.querySelectorAll('#star-input button').forEach(b=>b.classList.remove('lit'));
  selectedStars=0;
  closeModal('review-modal');
  showToast('Review submitted ✓');
}

// ══════════════════════════════════════════
//  NOTIFICATIONS
// ══════════════════════════════════════════
function renderNotifications() {
  document.getElementById('notif-list').innerHTML = notifications.length
    ? notifications.map((n,i)=>`
      <div class="noti ${n.unread?'unread':''}" onclick="openNotification(${i})">
        <div class="noti-dot"></div>
        <div><div class="ntitle">${n.title}</div><div class="nbody">${n.body}</div><div class="ntime">${n.time}</div></div>
        <i class="ti ti-chevron-right" style="color:var(--border);align-self:center;flex-shrink:0"></i>
      </div>`).join('')
    : '<div class="no-results"><i class="ti ti-bell-off"></i><p>No notifications yet.</p></div>';
  updateNotifDot();
}
function openNotification(i) {
  const n = notifications[i];
  if (!n) return;
  n.unread = false;
  updateNotifDot();
  const t = n.target;
  if (!t || !t.screen) { showToast('Notification opened'); renderNotifications(); return; }
  if (t.screen === 'search') {
    go('search');
    document.getElementById('main-search').value = '';
    searchQuery = '';
    document.getElementById('search-trending').style.display = 'none';
    document.getElementById('search-results').style.display  = 'block';
    document.querySelectorAll('#search-chips .chip').forEach(c=>{
      const label = c.textContent.trim();
      c.classList.toggle('active', t.cat ? label.includes(t.cat) : label==='All');
    });
    searchFilterCat = t.cat || 'All';
    renderSearchResults();
    showToast('Showing: '+(t.cat||'All listings'));
  } else if (t.screen === 'product' && t.id) {
    showProduct(t.id);
  } else {
    go(t.screen);
    showToast('Opened '+t.screen.replace('-',' '));
  }
}
function markAllRead() {
  notifications.forEach(n=>n.unread=false);
  renderNotifications(); showToast('All marked as read');
}
function updateNotifDot() {
  document.getElementById('notif-dot').style.display = notifications.some(n=>n.unread)?'block':'none';
}

// ══════════════════════════════════════════
//  ORDERS
// ══════════════════════════════════════════
function renderOrders() {
  document.getElementById('orders-list').innerHTML = ORDERS_DATA.length
    ? ORDERS_DATA.map(o=>`
      <div class="order-item" onclick="showToast('Order detail — ${o.title}')">
        <div class="order-emoji" style="background:var(--bg2)">${o.emoji}</div>
        <div style="flex:1"><div style="font-size:13px;font-weight:700;color:var(--txt)">${o.title}</div>
        <div style="font-size:13px;color:var(--g);font-weight:700">${o.price}</div>
        <div style="font-size:11px;color:var(--muted);margin-top:2px">${o.date}</div></div>
        <span class="o-status ${o.statusClass}">${o.status}</span>
      </div>`).join('')
    : '<div class="empty"><i class="ti ti-receipt-off"></i><p>No orders yet.<br>Add items to cart to get started.</p></div>';
}

// ══════════════════════════════════════════
//  WISHLIST
// ══════════════════════════════════════════
function renderWishlist() {
  const wished = PRODUCTS.filter(p=>wishlist.has(p.id));
  document.getElementById('wish-grid').innerHTML = wished.map(p=>productCard(p)).join('');
  document.getElementById('wish-empty').style.display = wished.length?'none':'flex';
  document.getElementById('wish-grid').style.display  = wished.length?'grid':'none';
}

// ══════════════════════════════════════════
//  SELL / PUBLISH
// ══════════════════════════════════════════
function publishListing() {
  const okT = validate('s-title');
  const okC = validate('s-cat');
  const okP = (() => {
    const el = document.getElementById('s-price');
    const v  = parseFloat(el.value);
    const ok = !isNaN(v) && v >= 0;
    el.classList.toggle('err', !ok);
    return ok;
  })();
  const okCo = validate('s-cond');
  const okD  = validate('s-desc');
  if (!okT||!okC||!okP||!okCo||!okD) { showToast('Please fill in required fields'); return; }
  const title  = document.getElementById('s-title').value.trim();
  const price  = parseFloat(document.getElementById('s-price').value);
  const cat    = document.getElementById('s-cat').value;
  const cond   = document.getElementById('s-cond').value;
  const desc   = document.getElementById('s-desc').value.trim();
  const img    = uploadedProductPhotos[0];
  const catEmojis = {'📚 Books':'📚','💻 Electronics':'💻','🍱 Food':'🍱','👕 Clothing':'👕','🛠 Services':'🛠','Other':'📦'};
  PRODUCTS.unshift({
    id:'user_'+Date.now(), emoji:catEmojis[cat]||'📦', bg:'var(--bg2)',
    price, priceDisp:'R '+price.toFixed(2), title, stars:5, reviews:0,
    seller:profileData.name, avaText:profileData.name.slice(0,2).toUpperCase(),
    avaBg:'var(--gl)', avaC:'var(--gd)', category:cat.replace(/[^\w\s]/g,'').trim(),
    condition:cond, desc, uploadedImg:img||null
  });
  // reset form
  resetSellForm();
  document.getElementById('stat-listings').textContent = parseInt(document.getElementById('stat-listings').textContent)+1;
  showToast('Listing published ✓');
  go('home');
}

// ══════════════════════════════════════════
//  ACCOUNT SETTINGS
// ══════════════════════════════════════════
function loadAccountSettings() {
  document.getElementById('acc-name').value   = profileData.name;
  document.getElementById('acc-email').value  = profileData.email;
  document.getElementById('acc-phone').value  = profileData.phone;
  document.getElementById('acc-campus').value = profileData.campus;
  const img = document.getElementById('acc-ava-img');
  const txt = document.getElementById('acc-ava-txt');
  if (profileData.avatarSrc) { img.src=profileData.avatarSrc; img.style.display='block'; txt.style.display='none'; }
  else { img.style.display='none'; txt.style.display='block'; txt.textContent=profileData.name.split(' ').map(w=>w[0]).join('').slice(0,2).toUpperCase(); }
}
function saveAccountSettings() {
  const name = document.getElementById('acc-name').value.trim();
  if (!name) { document.getElementById('acc-name').classList.add('err'); showToast('Name is required'); return; }
  profileData.name   = name;
  profileData.email  = document.getElementById('acc-email').value.trim() || profileData.email;
  profileData.phone  = document.getElementById('acc-phone').value.trim();
  profileData.campus = document.getElementById('acc-campus').value.trim();
  // Update profile display
  document.getElementById('profile-name').textContent  = profileData.name;
  document.getElementById('profile-email').textContent = profileData.email;
  document.getElementById('home-username').textContent = profileData.name.split(' ')[0];
  if (profileData.avatarSrc) {
    const img = document.getElementById('profile-ava-img');
    img.src=profileData.avatarSrc; img.style.display='block';
    document.getElementById('profile-ava-txt').style.display='none';
  } else {
    document.getElementById('profile-ava-txt').textContent = profileData.name.split(' ').map(w=>w[0]).join('').slice(0,2).toUpperCase();
  }
  showToast('Settings saved ✓');
  back();
}

// ══════════════════════════════════════════
//  PHOTO UPLOAD — SELL FORM
// ══════════════════════════════════════════
function triggerPhotoUpload(slotIndex) {
  currentPhotoSlot = slotIndex;
  document.getElementById('photo-input').value='';
  document.getElementById('photo-input').click();
}
function handlePhotoUpload(e) {
  const file = e.target.files[0];
  if (!file) return;
  const reader = new FileReader();
  reader.onload = ev => {
    const src = ev.target.result;
    uploadedProductPhotos[currentPhotoSlot] = src;
    const slot = document.getElementById('slot-'+currentPhotoSlot);
    slot.classList.add('has-img');
    // clear content, add img
    const existing = slot.querySelector('img');
    if (existing) existing.remove();
    const icon = slot.querySelector('i');
    const span = slot.querySelector('span:not(.rmv)');
    if (icon) icon.style.display='none';
    if (span) span.style.display='none';
    const img = document.createElement('img');
    img.src=src; img.alt='Photo'; img.style.cssText='position:absolute;inset:0;width:100%;height:100%;object-fit:cover;border-radius:var(--rmd)';
    slot.insertBefore(img, slot.querySelector('.rmv'));
    showToast('Photo added ✓');
  };
  reader.readAsDataURL(file);
}
function removePhoto(e,i) {
  e.stopPropagation();
  uploadedProductPhotos[i]=null;
  resetSlot(i);
  showToast('Photo removed');
}
function resetSlot(i) {
  const slot = document.getElementById('slot-'+i);
  slot.classList.remove('has-img');
  const img = slot.querySelector('img');
  if (img) img.remove();
  const icon = slot.querySelector('i');
  const span = slot.querySelector('span:not(.rmv)');
  if (icon) icon.style.display='';
  if (span) span.style.display='';
}

// ══════════════════════════════════════════
//  AVATAR UPLOAD
// ══════════════════════════════════════════
function triggerAvatarUpload() {
  document.getElementById('avatar-input').value='';
  document.getElementById('avatar-input').click();
}
function handleAvatarUpload(e) {
  const file = e.target.files[0];
  if (!file) return;
  const reader = new FileReader();
  reader.onload = ev => {
    profileData.avatarSrc = ev.target.result;
    // Profile page avatar
    const pImg = document.getElementById('profile-ava-img');
    pImg.src=ev.target.result; pImg.style.display='block';
    document.getElementById('profile-ava-txt').style.display='none';
    // Account settings preview
    const aImg = document.getElementById('acc-ava-img');
    aImg.src=ev.target.result; aImg.style.display='block';
    document.getElementById('acc-ava-txt').style.display='none';
    showToast('Profile photo updated ✓');
  };
  reader.readAsDataURL(file);
}

// ══════════════════════════════════════════
//  LANDING / AUTH
// ══════════════════════════════════════════
let isLoggedIn = false;
let isGuest = false;
function showAuthTab(which) {
  document.querySelectorAll('.auth-tab').forEach(t=>t.classList.remove('active'));
  document.querySelectorAll('.auth-form').forEach(f=>f.classList.remove('active'));
  document.getElementById('tab-'+which).classList.add('active');
  document.getElementById('form-'+which).classList.add('active');
  const titles = {signup:['Create your account','Join your campus marketplace in seconds.'],signin:['Welcome back','Sign in to continue to Community Store.']};
  document.getElementById('auth-title').textContent = titles[which][0];
  document.getElementById('auth-sub').textContent   = titles[which][1];
}
function togglePw(id, btn) {
  const el = document.getElementById(id);
  const isPw = el.type === 'password';
  el.type = isPw ? 'text' : 'password';
  btn.querySelector('i').className = isPw ? 'ti ti-eye-off' : 'ti ti-eye';
}
function handleSignup() {
  const okName = validate('su-name');
  const email  = document.getElementById('su-email').value.trim();
  const okEmail = !!email && /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email);
  document.getElementById('su-email').classList.toggle('err', !okEmail);
  const pw = document.getElementById('su-pw').value;
  const okPw = pw.length >= 8;
  document.getElementById('su-pw').classList.toggle('err', !okPw);
  if (!okName || !okEmail || !okPw) { showToast('Please check the highlighted fields'); return; }
  const name = document.getElementById('su-name').value.trim();
  profileData.name   = name;
  profileData.email  = email;
  profileData.campus = document.getElementById('su-campus').value.trim();
  finishAuth(`Welcome, ${name.split(' ')[0]}! Account created ✓`);
}
function handleSignin() {
  const email = document.getElementById('si-email').value.trim();
  const okEmail = !!email;
  document.getElementById('si-email').classList.toggle('err', !okEmail);
  const pw = document.getElementById('si-pw').value;
  const okPw = !!pw;
  document.getElementById('si-pw').classList.toggle('err', !okPw);
  if (!okEmail || !okPw) { showToast('Please enter your email and password'); return; }
  // Demo sign-in: keep existing profile, just swap in the typed email
  profileData.email = email;
  finishAuth(`Welcome back, ${profileData.name.split(' ')[0]}! ✓`);
}
function continueAsGuest() {
  isGuest = true;
  profileData.name = 'Guest Student';
  profileData.email = 'guest@campus.ac.za';
  isLoggedIn = false;
  document.getElementById('profile-name').textContent  = profileData.name;
  document.getElementById('profile-email').textContent = profileData.email;
  document.getElementById('home-username').textContent = 'Guest';
  document.getElementById('profile-ava-txt').textContent = 'GS';
  history = ['home'];
  go('home');
  showToast('Browsing as guest');
}
function finishAuth(msg) {
  isLoggedIn = true;
  isGuest = false;
  document.getElementById('profile-name').textContent  = profileData.name;
  document.getElementById('profile-email').textContent = profileData.email;
  document.getElementById('home-username').textContent = profileData.name.split(' ')[0];
  document.getElementById('profile-ava-txt').textContent = profileData.name.split(' ').map(w=>w[0]).join('').slice(0,2).toUpperCase();
  history = ['home'];
  go('home');
  showToast(msg);
}
function signOut() {
  isLoggedIn = false;
  isGuest = false;
  clearCart();
  history = ['landing'];
  go('landing');
  showAuthTab('signin');
  showToast('Signed out successfully');
}
function confirmSignOut() {
  showConfirm('Sign out?', "You'll be taken back to the welcome screen and your cart will be cleared.", 'Sign out', signOut, true);
}

// ══════════════════════════════════════════
//  GUEST GATE
// ══════════════════════════════════════════
function requireAuth(featureTitle, featureMsg) {
  if (isLoggedIn) return true;
  document.getElementById('gate-title').textContent = featureTitle || 'Sign in required';
  document.getElementById('gate-msg').textContent = featureMsg || 'Create a free account or sign in to use this feature.';
  openModal('guest-gate-modal');
  return false;
}

// Screens that guests cannot access
const GATED_SCREENS = ['cart','checkout','sell','post-bulletin','orders','account-settings','privacy','wishlist','notifications'];



// ══════════════════════════════════════════
//  DISCARD CONFIRMATIONS
// ══════════════════════════════════════════
function resetSellForm() {
  ['s-title','s-desc','s-loc'].forEach(id=>{const el=document.getElementById(id);el.value='';el.classList.remove('err');});
  ['s-cat','s-cond','s-price'].forEach(id=>{const el=document.getElementById(id);if(el.tagName==='SELECT')el.selectedIndex=0;else el.value='';el.classList.remove('err');});
  for(let i=0;i<5;i++){uploadedProductPhotos[i]=null;resetSlot(i);}
}
function confirmDiscardSell() {
  const dirty = document.getElementById('s-title').value.trim() || document.getElementById('s-desc').value.trim() || document.getElementById('s-price').value.trim() || uploadedProductPhotos.some(p=>p);
  if (!dirty) { back(); return; }
  showConfirm('Discard listing?', 'Your photos and listing details will be lost.', 'Discard', ()=>{ resetSellForm(); back(); }, true);
}
function confirmDiscardBulletin() {
  const dirty = document.getElementById('pb-title').value.trim() || document.getElementById('pb-details').value.trim();
  if (!dirty) { back(); return; }
  showConfirm('Discard announcement?', 'Your draft announcement will be lost.', 'Discard', ()=>{
    ['pb-cat','pb-title','pb-details','pb-contact'].forEach(id=>{const el=document.getElementById(id);el.value='';el.classList.remove('err');});
    back();
  }, true);
}
function confirmDiscardSettings() {
  const changed = document.getElementById('acc-name').value.trim() !== profileData.name
    || document.getElementById('acc-email').value.trim() !== profileData.email
    || document.getElementById('acc-phone').value.trim() !== (profileData.phone||'')
    || document.getElementById('acc-campus').value.trim() !== (profileData.campus||'');
  if (!changed) { back(); return; }
  showConfirm('Discard changes?', 'Your unsaved profile changes will be lost.', 'Discard', back, true);
}

// ══════════════════════════════════════════
//  MODALS
// ══════════════════════════════════════════
function openModal(id) {
  document.getElementById(id).classList.add('open');
}
function closeModal(id) {
  document.getElementById(id).classList.remove('open');
}
let confirmCallback = null;
function showConfirm(title, msg, confirmLabel, cb, danger) {
  document.getElementById('confirm-title').textContent = title;
  document.getElementById('confirm-msg').textContent = msg;
  const btn = document.getElementById('confirm-btn-action');
  btn.textContent = confirmLabel;
  btn.className = danger ? 'btn btn-g' : 'btn btn-g';
  btn.style.background = danger ? 'var(--red)' : '';
  confirmCallback = cb;
  openModal('confirm-modal');
}
function runConfirm() {
  const cb = confirmCallback;
  closeModal('confirm-modal');
  confirmCallback = null;
  if (cb) cb();
}

// ══════════════════════════════════════════
//  MESSAGE SELLER
// ══════════════════════════════════════════
function sendMessage() {
  if (!requireAuth('Sign in to message sellers', 'Create an account to contact sellers directly.')) return;
  const text = document.getElementById('msg-text').value.trim();
  if (!text) { document.getElementById('msg-text').classList.add('err'); showToast('Please write a message'); return; }
  closeModal('msg-modal');
  notifications.unshift({title:'Message sent', body:`Your message to ${document.getElementById('msg-seller-name').textContent}: "${text.slice(0,60)}…"`, time:'Just now', unread:false, target:{screen:'product', id:currentProductId}});
  document.getElementById('msg-text').value='';
  document.getElementById('msg-name').value='';
  showToast('Message sent ✓');
}

// ══════════════════════════════════════════
//  PASSWORD STRENGTH
// ══════════════════════════════════════════
document.getElementById('new-pw').addEventListener('input', function() {
  const v=this.value, l=v.length;
  let score=0;
  if (l>=8) score++;
  if (/[A-Z]/.test(v)) score++;
  if (/[0-9]/.test(v)) score++;
  if (/[^A-Za-z0-9]/.test(v)) score++;
  const pct=[0,25,50,75,100][score];
  const colours=['var(--red)','var(--red)','var(--amber)','var(--g)','var(--g)'];
  const hints=['Enter a new password','Too short','Add numbers or symbols','Getting stronger','Strong password ✓'];
  document.getElementById('pw-strength').style.width=pct+'%';
  document.getElementById('pw-strength').style.background=colours[score];
  document.getElementById('pw-hint').textContent=hints[score];
});

// ══════════════════════════════════════════
//  2FA TOGGLE ANIMATION
// ══════════════════════════════════════════
document.getElementById('tfa-tog').addEventListener('change', function() {
  document.getElementById('tfa-track').style.background = this.checked?'var(--g)':'var(--bg3)';
  document.getElementById('tfa-thumb').style.transform = this.checked?'translateX(20px)':'translateX(0)';
});

// ══════════════════════════════════════════
//  TOAST
// ══════════════════════════════════════════
let toastTimer;
function showToast(msg) {
  const t=document.getElementById('toast');
  t.textContent=msg; t.classList.add('show');
  clearTimeout(toastTimer);
  toastTimer=setTimeout(()=>t.classList.remove('show'), 2500);
}

// ══════════════════════════════════════════
//  KEYBOARD
// ══════════════════════════════════════════
document.addEventListener('keydown', e=>{
  if (e.key==='Escape') {
    document.querySelectorAll('.modal-bg.open').forEach(m=>m.classList.remove('open'));
  }
  if ((e.key==='Enter'||e.key===' ') && document.activeElement.getAttribute('role')==='radio') {
    document.activeElement.click();
  }
});

// ══════════════════════════════════════════
//  INIT
// ══════════════════════════════════════════
renderHomeGrids();
renderBulletin();
renderNotifications();
updateNotifDot();
updateWishlistBadge();
document.querySelector('.nav').style.display='none';
</script>
</body>
</html>
