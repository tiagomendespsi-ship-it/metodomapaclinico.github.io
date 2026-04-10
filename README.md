&lt;!DOCTYPE html&gt;
&lt;html lang=&quot;pt-BR&quot;&gt;
&lt;head&gt;
&lt;meta charset=&quot;UTF-8&quot;&gt;
&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0&quot;&gt;
&lt;title&gt;Clínica na Prática — Método M.A.P.A. Clínico&lt;/title&gt;
&lt;link
href=&quot;https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;0,90
0;1,400&amp;family=DM+Sans:wght@300;400;500;600&amp;display=swap&quot; rel=&quot;stylesheet&quot;&gt;
&lt;style&gt;
:root {
--ink: #0f1923;
--deep: #132238;
--teal: #1a5c6e;
--teal-light: #2a8a9e;
--gold: #c89a44;
--gold-light: #e8bf7a;
--cream: #f5f0e8;
--warm: #faf7f2;
--muted: #6b7a8a;
--white: #ffffff;
}
* { margin: 0; padding: 0; box-sizing: border-box; }
body {
background: var(--warm);
font-family: &#39;DM Sans&#39;, sans-serif;
color: var(--ink);
overflow-x: hidden;
}
/* ── HERO ── */
.hero {
background: var(--deep);
position: relative;
overflow: hidden;
padding: 80px 40px 70px;
text-align: center;
}
.hero::before {
content: &#39;&#39;;
position: absolute;
inset: 0;
background:
radial-gradient(ellipse 80% 60% at 50% 0%, rgba(26,92,110,0.5) 0%, transparent 70%),
radial-gradient(ellipse 50% 50% at 90% 100%, rgba(200,154,68,0.15) 0%, transparent
60%);

}
.hero-badge {
position: relative;
display: inline-block;
border: 1px solid rgba(200,154,68,0.5);
color: var(--gold-light);
font-size: 11px;
font-weight: 600;
letter-spacing: 3px;
text-transform: uppercase;
padding: 6px 18px;
border-radius: 20px;
margin-bottom: 28px;
backdrop-filter: blur(4px);
background: rgba(200,154,68,0.08);
}
.hero h1 {
position: relative;
font-family: &#39;Playfair Display&#39;, serif;
font-size: clamp(2rem, 5vw, 3.2rem);
font-weight: 900;
color: var(--white);
line-height: 1.15;
max-width: 850px;
margin: 0 auto 12px;
}
.hero h1 em { font-style: italic; color: var(--gold-light); }
.hero-sub {
position: relative;
font-size: 1.15rem;
color: rgba(255,255,255,0.65);
max-width: 560px;
margin: 0 auto 36px;
line-height: 1.6;
}
.hero-desc {
position: relative;
background: rgba(255,255,255,0.07);
border: 1px solid rgba(255,255,255,0.1);
border-radius: 14px;
padding: 22px 30px;
max-width: 600px;
margin: 0 auto 32px;
color: rgba(255,255,255,0.8);
font-size: 0.95rem;
line-height: 1.7;
}
.hero-cta {

position: relative;
display: inline-block;
background: linear-gradient(135deg, var(--gold) 0%, #a87a2a 100%);
color: var(--deep);
font-family: &#39;DM Sans&#39;, sans-serif;
font-size: 1rem;
font-weight: 700;
padding: 16px 38px;
border-radius: 50px;
cursor: pointer;
border: none;
box-shadow: 0 8px 30px rgba(200,154,68,0.35);
transition: transform 0.2s, box-shadow 0.2s;
}
.hero-cta:hover { transform: translateY(-3px) scale(1.02); box-shadow: 0 14px 40px
rgba(200,154,68,0.5); }
/* ── SECTIONS ── */
.section { padding: 70px 40px; max-width: 860px; margin: 0 auto; }
.section-label { font-size: 10.5px; font-weight: 700; letter-spacing: 3.5px; text-transform:
uppercase; color: var(--teal-light); margin-bottom: 14px; }
.section-title { font-family: &#39;Playfair Display&#39;, serif; font-size: clamp(1.6rem, 3.5vw, 2.3rem);
font-weight: 700; color: var(--deep); line-height: 1.25; margin-bottom: 32px; }
.section-title span { color: var(--teal); }
.divider { width: 48px; height: 3px; background: linear-gradient(90deg, var(--gold),
transparent); border-radius: 2px; margin-bottom: 32px; }
.pain-section { background: var(--cream); border-radius: 24px; padding: 52px 48px;
position: relative; }
.pain-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; margin-bottom: 28px; }
.pain-item { background: white; border-radius: 12px; padding: 16px 18px; border-left: 3px
solid var(--teal); font-size: 0.9rem; display: flex; align-items: flex-start; gap: 10px; }
.pain-truth { background: var(--deep); color: white; border-radius: 12px; padding: 20px; text-
align: center; border-left: 4px solid var(--gold); }
/* ── MAPA ── */
.mapa-section { background: var(--deep); padding: 70px 40px; color: white; }
.mapa-cards { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
.mapa-card { background: rgba(255,255,255,0.05); border: 1px solid
rgba(255,255,255,0.1); border-radius: 18px; padding: 32px 28px; transition: 0.3s; }
.mapa-card:hover { border-color: var(--gold); transform: translateY(-5px); }
.mapa-letter { font-family: &#39;Playfair Display&#39;, serif; font-size: 3.5rem; font-weight: 900; color:
var(--gold); margin-bottom: 5px; }
.mapa-word { font-size: 0.8rem; font-weight: 700; color: var(--gold-light); letter-spacing: 2px;
text-transform: uppercase; margin-bottom: 10px; }
.mapa-desc { font-size: 0.9rem; color: rgba(255,255,255,0.7); line-height: 1.6; }
/* ── TEACHER ── */

.teacher-card { background: white; border-radius: 22px; padding: 40px; display: flex; gap:
36px; align-items: center; border: 1px solid rgba(26,92,110,0.1); box-shadow: 0 12px 40px
rgba(0,0,0,0.06); }
.teacher-avatar { width: 100px; height: 100px; border-radius: 50%; background: var(--deep);
display: flex; align-items: center; justify-content: center; flex-shrink: 0; font-family: &#39;Playfair
Display&#39;, serif; font-size: 2.2rem; color: var(--gold-light); font-weight: 900; border: 3px solid
var(--gold); }
.teacher-info h3 { font-family: &#39;Playfair Display&#39;, serif; font-size: 1.6rem; color: var(--deep);
margin-bottom: 8px; }
.teacher-info p { font-size: 0.95rem; color: var(--muted); line-height: 1.7; }
.tag { background: var(--cream); color: var(--teal); border-radius: 20px; padding: 5px 14px;
font-size: 0.78rem; font-weight: 600; display: inline-block; margin: 4px 2px; border: 1px solid
rgba(26,92,110,0.2); }
/* ANIMATION CLASS */
.io { opacity: 0; transform: translateY(20px); transition: all 0.6s ease-out; }
.io.visible { opacity: 1; transform: translateY(0); }
@media (max-width: 640px) {
.pain-grid, .mapa-cards { grid-template-columns: 1fr; }
.teacher-card { flex-direction: column; text-align: center; }
}
&lt;/style&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;section class=&quot;hero&quot;&gt;
&lt;div class=&quot;hero-badge&quot;&gt;Aperfeiçoamento Profissional&lt;/div&gt;
&lt;h1&gt;Domine o raciocínio clínico com o &lt;br&gt;&lt;em&gt;Método M.A.P.A.&lt;/em&gt;&lt;/h1&gt;
&lt;p class=&quot;hero-sub&quot;&gt;Uma ponte segura entre a teoria acadêmica e o primeiro
atendimento, desenvolvida para psicólogos que buscam excelência técnica.&lt;/p&gt;
&lt;div class=&quot;hero-desc&quot;&gt;Transforme a insegurança do início de carreira em uma prática
estruturada com bases na Análise do Comportamento e TCC.&lt;/div&gt;
&lt;button class=&quot;hero-cta&quot;&gt;Quero dominar o Método M.A.P.A.&lt;/button&gt;
&lt;/section&gt;
&lt;div class=&quot;section&quot;&gt;
&lt;p class=&quot;section-label io&quot;&gt;Raciocínio Clínico&lt;/p&gt;
&lt;h2 class=&quot;section-title io&quot;&gt;A graduação deu a base,&lt;br&gt;&lt;span&gt;nós damos a
estrutura.&lt;/span&gt;&lt;/h2&gt;
&lt;div class=&quot;divider io&quot;&gt;&lt;/div&gt;
&lt;div class=&quot;pain-section io&quot;&gt;
&lt;div class=&quot;pain-grid&quot;&gt;
&lt;div class=&quot;pain-item&quot;&gt;Dificuldade em realizar a Análise Funcional do caso.&lt;/div&gt;
&lt;div class=&quot;pain-item&quot;&gt;Insegurança na condução da primeira sessão.&lt;/div&gt;
&lt;div class=&quot;pain-item&quot;&gt;Sensação de que a terapia &quot;travou&quot; ou está sem rumo.&lt;/div&gt;
&lt;div class=&quot;pain-item&quot;&gt;Dúvidas sobre qual técnica aplicar em cada demanda.&lt;/div&gt;
&lt;/div&gt;

&lt;div class=&quot;pain-truth&quot;&gt;Muitos profissionais se sentem &quot;improvisando&quot; por falta de um
&lt;strong&gt;processo claro de tomada de decisão clínica.&lt;/strong&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;section class=&quot;mapa-section&quot;&gt;
&lt;div class=&quot;section&quot; style=&quot;padding: 0 0 50px 0;&quot;&gt;
&lt;p class=&quot;section-label&quot; style=&quot;color: var(--gold-light)&quot;&gt;A Metodologia&lt;/p&gt;
&lt;h2 class=&quot;section-title&quot; style=&quot;color: white&quot;&gt;O Método &lt;span&gt;M.A.P.A.
Clínico&lt;/span&gt;&lt;/h2&gt;
&lt;div class=&quot;mapa-cards&quot;&gt;
&lt;div class=&quot;mapa-card io&quot;&gt;
&lt;div class=&quot;mapa-letter&quot;&gt;M&lt;/div&gt;
&lt;div class=&quot;mapa-word&quot;&gt;Mapeamento e Análise&lt;/div&gt;
&lt;p class=&quot;mapa-desc&quot;&gt;Identificação de variáveis mantenedoras, história de
reforçamento e queixa principal através de um olhar funcional.&lt;/p&gt;
&lt;/div&gt;
&lt;div class=&quot;mapa-card io&quot;&gt;
&lt;div class=&quot;mapa-letter&quot;&gt;A&lt;/div&gt;
&lt;div class=&quot;mapa-word&quot;&gt;Aliança Estratégica&lt;/div&gt;
&lt;p class=&quot;mapa-desc&quot;&gt;Técnicas validadas para construção de vínculo e manejo da
relação terapêutica desde o primeiro contato.&lt;/p&gt;
&lt;/div&gt;
&lt;div class=&quot;mapa-card io&quot;&gt;
&lt;div class=&quot;mapa-letter&quot;&gt;P&lt;/div&gt;
&lt;div class=&quot;mapa-word&quot;&gt;Planejamento Técnico&lt;/div&gt;
&lt;p class=&quot;mapa-desc&quot;&gt;Hierarquização de metas e seleção de intervenções baseadas
em evidências para cada perfil de paciente.&lt;/p&gt;
&lt;/div&gt;
&lt;div class=&quot;mapa-card io&quot;&gt;
&lt;div class=&quot;mapa-letter&quot;&gt;A&lt;/div&gt;
&lt;div class=&quot;mapa-word&quot;&gt;Acompanhamento de Resultados&lt;/div&gt;
&lt;p class=&quot;mapa-desc&quot;&gt;Uso de indicadores de progresso clínico e ajustes dinâmicos
para garantir a evolução do processo.&lt;/p&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/section&gt;
&lt;div class=&quot;section&quot;&gt;
&lt;p class=&quot;section-label io&quot;&gt;Docência e Prática&lt;/p&gt;
&lt;div class=&quot;divider io&quot;&gt;&lt;/div&gt;
&lt;div class=&quot;teacher-card io&quot;&gt;
&lt;div class=&quot;teacher-avatar&quot;&gt;TM&lt;/div&gt;
&lt;div class=&quot;teacher-info&quot;&gt;
&lt;h3&gt;Tiago Mendes&lt;/h3&gt;

&lt;p&gt;Psicólogo e Professor Universitário. Mestre em Psicologia com foco em análise
comportamental e intervenções baseadas em evidências. Dedica sua carreira a transformar
a teoria acadêmica em prática clínica segura e ética para novos profissionais.&lt;/p&gt;
&lt;div class=&quot;teacher-tags&quot;&gt;
&lt;span class=&quot;tag&quot;&gt;Mestre em Psicologia&lt;/span&gt;
&lt;span class=&quot;tag&quot;&gt;Docente de EBA&lt;/span&gt;
&lt;span class=&quot;tag&quot;&gt;Especialista em TCC&lt;/span&gt;
&lt;span class=&quot;tag&quot;&gt;Supervisor Clínico&lt;/span&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;section class=&quot;offer-section&quot; style=&quot;background: var(--deep); padding: 80px 40px; text-
align: center; color: white;&quot;&gt;
&lt;h2 class=&quot;section-title&quot; style=&quot;color: white; margin-bottom: 20px;&quot;&gt;Pronto para
transformar sua clínica?&lt;/h2&gt;
&lt;p style=&quot;margin-bottom: 40px; opacity: 0.8;&quot;&gt;Acesso imediato às 20 aulas e à biblioteca
de 100+ ferramentas.&lt;/p&gt;
&lt;button class=&quot;hero-cta&quot;&gt;Quero me inscrever agora&lt;/button&gt;
&lt;/section&gt;
&lt;script&gt;
const observer = new IntersectionObserver((entries) =&gt; {
entries.forEach(entry =&gt; {
if (entry.isIntersecting) entry.target.classList.add(&#39;visible&#39;);
});
}, { threshold: 0.1 });
document.querySelectorAll(&#39;.io&#39;).forEach(el =&gt; observer.observe(el));
&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
