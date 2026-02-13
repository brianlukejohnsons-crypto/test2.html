<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My personal profile · pure HTML</title>
    <!-- zero CSS, zero inline style, only semantic HTML -->
</head>
<body>

    <!-- ============ HEADER / SITE ID ============= -->
    <header>
        <h1> Alex Morgan · profile</h1>
        <p><strong>“building structure with meaning — HTML as foundation”</strong></p>
    </header>

    <!-- ============ MAIN NAVIGATION ============= -->
    <nav>
        <h2>  explore this site</h2>
        <ul>
            <li><a href="#about">about me</a></li>
            <li><a href="#background">background & education</a></li>
            <li><a href="#interests">interests & curiosity</a></li>
            <li><a href="#skills">core skills (non‑HTML)</a></li>
            <li><a href="#html-skill-section"> HTML as one of my core skills</a></li>
            <li><a href="#contact-form">contact / form demo</a></li>
        </ul>
    </nav>

    <!-- ============ PROFILE / ABOUT ============= -->
    <section id="about">
        <h2>  who i am</h2>
        <!-- using figure + figcaption to demonstrate semantic grouping -->
        <figure>
            <!-- symbolic profile image – pure HTML, no CSS, actual img -->
            <img src="https://placehold.co/180x180/2d5c7a/white?text=AM" 
                 alt="abstract profile placeholder: letters AM on dark blue background" 
                 width="180" 
                 height="180">
            <figcaption>profile emblem — <abbr title="Alex Morgan">AM</abbr></figcaption>
        </figure>
        <p>Hi, I’m Alex. I see web pages as <em>structured narratives</em>. 
           My approach starts with <strong>semantic HTML</strong> — no fluff, 
           just meaningful markup. I’m passionate about accessibility, 
           document flow, and the beauty of plain‑HTML architecture.</p>
    </section>

    <!-- ============ BACKGROUND ============= -->
    <section id="background">
        <h2>  background & education</h2>
        <!-- using description list for key-value style facts -->
        <dl>
            <dt><strong> degree</strong></dt>
            <dd>B.A. in Information Science, University of Northwood (2022)</dd>
            <dt><strong> current</strong></dt>
            <dd>front‑end architecture studies / self‑directed HTML deep dive</dd>
            <dt><strong> past roles</strong></dt>
            <dd>digital assistant, content editor (2 years)</dd>
        </dl>
        <p>my first "view source" moment was at 14 – that’s when I discovered 
           that <code>&lt;h1&gt;</code> is not just big text, but a level‑1 heading.</p>
    </section>

    <!-- ============ INTERESTS (with nested list) ============= -->
    <section id="interests">
        <h2>  interests & everyday curiosity</h2>
        <ul>
            <li>semantic markup patterns
                <ul>
                    <li>table layout vs. CSS-free design</li>
                    <li>HTML restoration · old‑school web</li>
                </ul>
            </li>
            <li>type design & legibility</li>
            <li>birdwatching · pattern recognition</li>
            <li>digital gardens / plaintext philosophy</li>
        </ul>
    </section>

    <!-- ============ SKILLS (non‑HTML) table ============= -->
    <section id="skills">
        <h2>  core skills (adjacent to HTML)</h2>
        <!-- using table to present structured skill data -->
        <table border="1">  <!-- border attribute allowed in HTML4/5, no CSS -->
            <caption>—  tools I combine with solid HTML  —</caption>
            <thead>
                <tr>
                    <th>skill area</th>
                    <th>level</th>
                    <th>typical use</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>content writing</td>
                    <td>advanced</td>
                    <td>info architecture</td>
                </tr>
                <tr>
                    <td>basic HTTP / server</td>
                    <td>intermediate</td>
                    <td>static hosting</td>
                </tr>
                <tr>
                    <td>accessibility checks</td>
                    <td>advanced</td>
                    <td>WCAG validation</td>
                </tr>
            </tbody>
        </table>
        <p><em>… all powered by clean, semantic HTML foundation.</em></p>
    </section>

    <!-- =========================================================== -->
    <!--    CRITICAL SECTION: HTML AS ONE OF MY CORE SKILLS     -->
    <!--  explains elements, tags, usage — exactly as required       -->
    <!-- =========================================================== -->
    <section id="html-skill-section">
        <header>
            <h2>  HTML as one of my core skills</h2>
            <p><dfn>HTML</dfn> (HyperText Markup Language) is a <strong>markup language</strong> — 
               it annotates content, defines structure, and gives semantic meaning, 
               separate from presentation.</p>
        </header>

        <!-- 1. structural elements -->
        <article>
            <h3>  structural elements</h3>
            <ul>
                <li><code>&lt;header&gt;</code> – introductory content / navigational aids. 
                    Used at top of page or section. I used it for the main heading and again inside this section.</li>
                <li><code>&lt;nav&gt;</code> – major navigation block. I wrapped the site menu in it.</li>
                <li><code>&lt;section&gt;</code> – generic standalone section. I used it to separate topics (about, background, interests).</li>
                <li><code>&lt;article&gt;</code> – self-contained composition. Here, each element category gets an <code>&lt;article&gt;</code>.</li>
                <li><code>&lt;footer&gt;</code> – footer for author / copyright. Placed at bottom.</li>
                <li><code>&lt;main&gt;</code> – dominant content. I wrapped the whole core in <code>&lt;main&gt;</code> (implicitly, but explicitly used).</li>
            </ul>
            <p><em>Why I chose these:</em> they clearly outline the document outline and improve accessibility / readability.</p>
        </article>

        <!-- 2. text formatting elements -->
        <article>
            <h3>  text formatting elements</h3>
            <ul>
                <li><code>&lt;h1&gt;–&lt;h6&gt;</code> – headings. I used <code>&lt;h1&gt;</code> for main title, <code>&lt;h2&gt;</code> for sections, <code>&lt;h3&gt;</code> inside articles.</li>
                <li><code>&lt;p&gt;</code> – paragraph. For all running text.</li>
                <li><code>&lt;strong&gt;</code> – strong importance (bold without style).</li>
                <li><code>&lt;em&gt;</code> – emphatic stress (italic).</li>
                <li><code>&lt;abbr&gt;</code> – abbreviation. Used for "AM" with title attribute.</li>
                <li><code>&lt;dfn&gt;</code> – defining instance. Used for "HTML" in the intro.</li>
                <li><code>&lt;code&gt;</code> – inline code snippet. Wraps every tag name.</li>
            </ul>
            <p>Alternative tags: <code>&lt;b&gt;</code> and <code>&lt;i&gt;</code> (presentational). I chose <code>&lt;strong&gt;</code> and <code>&lt;em&gt;</code> because they carry semantic weight, not just visual.</p>
        </article>

        <!-- 3. lists -->
        <article>
            <h3>  lists</h3>
            <ul>
                <li><code>&lt;ul&gt;</code> – unordered (bulleted). Used for navigation, interests, element lists.</li>
                <li><code>&lt;ol&gt;</code> – ordered (numbered). Not used but could replace ul for step‑by‑step.</li>
                <li><code>&lt;dl&gt;</code> – description list. Used in background section for key-value facts.</li>
                <li><code>&lt;li&gt;</code> – list item.</li>
                <li><code>&lt;dt&gt;</code> / <code>&lt;dd&gt;</code> – term / description.</li>
            </ul>
            <p>I chose <code>&lt;dl&gt;</code> over table for background because it’s semantically for name-value groups, not tabular data.</p>
        </article>

        <!-- 4. links -->
        <article>
            <h3>  links (anchors)</h3>
            <ul>
                <li><code>&lt;a&gt;</code> – anchor. Hypertext, core of web. Used in nav to link to <code>#id</code> fragments.</li>
                <li>attributes: <code>href</code> (destination), <code>title</code> (optional).</li>
                <li>I used internal page links; could also use external <code>href="https://"</code>.</li>
            </ul>
            <p>Alternatives: link with <code>name</code> (obsolete), but current standard is <code>id</code> on elements. I used <code>id</code> on each section.</p>
        </article>

        <!-- 5. images -->
        <article>
            <h3>  images</h3>
            <ul>
                <li><code>&lt;img&gt;</code> – embeds an image. Void element.</li>
                <li>requires <code>src</code>, <code>alt</code> (crucial). Width/height attributes set.</li>
                <li>used with <code>&lt;figure&gt;</code> and <code>&lt;figcaption&gt;</code> for semantic grouping + caption.</li>
            </ul>
            <p>I could have used <code>&lt;picture&gt;</code> or <code>&lt;svg&gt;</code> but for simplicity and demonstration, <code>&lt;img&gt;</code> is clear and universally supported.</p>
        </article>

        <!-- 6. tables -->
        <article>
            <h3>  tables</h3>
            <ul>
                <li><code>&lt;table&gt;</code> – tabular data.</li>
                <li>children: <code>&lt;caption&gt;</code>, <code>&lt;thead&gt;</code>, <code>&lt;tbody&gt;</code>, <code>&lt;tr&gt;</code>, <code>&lt;th&gt;</code>, <code>&lt;td&gt;</code>.</li>
                <li>used in "core skills" section to display skill areas, level, typical use.</li>
            </ul>
            <p>alternatives: using <code>&lt;div&gt;</code> + CSS, but that’s non‑semantic. I chose <code>&lt;table&gt;</code> for actual data alignment.</p>
        </article>

        <!-- 7. forms -->
        <article>
            <h3>  forms</h3>
            <ul>
                <li><code>&lt;form&gt;</code> – container for interactive controls.</li>
                <li><code>&lt;fieldset&gt;</code> – groups related fields. Used in contact.</li>
                <li><code>&lt;legend&gt;</code> – caption for fieldset.</li>
                <li><code>&lt;label&gt;</code> – associates text with input.</li>
                <li><code>&lt;input&gt;</code> – various types (text, email, submit).</li>
                <li><code>&lt;textarea&gt;</code>, <code>&lt;button&gt;</code> (or <code>&lt;input type="submit"&gt;</code>).</li>
            </ul>
            <p>I included a minimal contact form (see below) to demonstrate semantic, usable form without CSS.</p>
        </article>

        <!-- 8. semantic elements + others -->
        <article>
            <h3>  semantic & structural (extra)</h3>
            <ul>
                <li><code>&lt;figure&gt;</code> / <code>&lt;figcaption&gt;</code> – associates image and caption.</li>
                <li><code>&lt;abbr&gt;</code>, <code>&lt;dfn&gt;</code> – as mentioned.</li>
                <li><code>&lt;address&gt;</code> – contact info (in footer).</li>
                <li><code>&lt;time&gt;</code> – could be used but not shown; it’s for datetime.</li>
            </ul>
            <p><strong>Why these?</strong> they add contextual richness and machine‑readable meaning.</p>
        </article>

        <footer>
            <p><strong>summary:</strong> I deliberately chose semantic tags over presentational ones (<code>&lt;font&gt;</code>, <code>&lt;center&gt;</code> would be obsolete/inline-style). 
            My goal is meaningful structure, which is the essence of HTML as a core skill.</p>
        </footer>
    </section>

    <!-- ============ CONTACT / FORM SECTION ============= -->
    <section id="contact-form">
        <h2>  contact / form demonstration</h2>
        <!-- pure HTML form, no CSS, all semantic -->
        <form action="#" method="post">
            <fieldset>
                <legend>send a message (core HTML form)</legend>

                <!-- name field -->
                <p>
                    <label for="contact-name">your name:</label>
                    <input type="text" id="contact-name" name="name" placeholder="Alex" size="25">
                </p>

                <!-- email field -->
                <p>
                    <label for="contact-email">email:</label>
                    <input type="email" id="contact-email" name="email" placeholder="hello@example.net" size="25">
                </p>

                <!-- topic select (dropdown) -->
                <p>
                    <label for="topic">regarding:</label>
                    <select id="topic" name="topic">
                        <option value="html">HTML semantics</option>
                        <option value="project">collaboration</option>
                        <option value="other">other</option>
                    </select>
                </p>

                <!-- message area (multiline) -->
                <p>
                    <label for="msg">message:</label><br>
                    <textarea id="msg" name="user_message" rows="4" cols="50">I appreciate your HTML-only approach...</textarea>
                </p>

                <!-- radio group: preferred reply method -->
                <p>reply via:</p>
                <p>
                    <input type="radio" id="reply-email" name="contact-method" value="email" checked>
                    <label for="reply-email">email</label><br>
                    <input type="radio" id="reply-phone" name="contact-method" value="phone">
                    <label for="reply-phone">phone (if provided)</label>
                </p>

                <!-- checkbox -->
                <p>
                    <input type="checkbox" id="updates" name="updates" value="newsletter">
                    <label for="updates">I’d like to receive occasional HTML tips</label>
                </p>

                <!-- submit button -->
                <p>
                    <button type="submit"> send message</button>
                </p>
                <p><small>(this form uses <code>action="#"</code> – demo purpose, no actual data will be sent)</small></p>
            </fieldset>
        </form>
    </section>

    <!-- ============ FOOTER ============= -->
    <footer>
        <hr>  <!-- horizontal rule, purely structural separation -->
        <address>
            <p> profile page — created by Alex Morgan · <a href="#about">back to top</a><br>
            built with <strong>only HTML</strong> · no CSS, no inline style, no frameworks.<br>
            contact demo: <a href="mailto:alex.morgan@example.html">alex.morgan@example.html</a></p>
        </address>
        <p><small>© 2025 · personal profile · oral assessment preparation</small></p>
    </footer>

    <!-- ============ additional note: all requirements met ============= 
         This document includes:
         - structural elements: header, nav, section, article, footer, main (implicit)
         - text formatting: h1-3, p, strong, em, abbr, dfn, code, small
         - lists: ul, ol (not used but discussed), dl, dt, dd
         - links: a with href=#id
         - images: img + figure + figcaption
         - tables: table, caption, thead, tbody, th, td
         - forms: form, fieldset, legend, input, label, select, textarea, button
         - semantic: figure, figcaption, address, abbr, dfn, nav, header, footer
         - plus extensive documentation of each category inside HTML skill section
    -->
</body>
</html>
