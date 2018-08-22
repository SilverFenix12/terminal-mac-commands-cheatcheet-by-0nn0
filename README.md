# terminal-mac-commands-cheatcheet-by-0nn0
Cheatsheet for Terminal commands in Mac

The contents in this file were pulled from https://github.com/0nn0/terminal-mac-cheatsheet for personal use. All Credits,Rights and licensing belong to <a href="https://github.com/0nn0/">0nn0</a>

<article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-terminal-cheatsheet-for-mac-basics" class="anchor" aria-hidden="true" href="#terminal-cheatsheet-for-mac-basics"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Terminal Cheatsheet for Mac (Basics)</h1>

<hr>
<p><em>Letters are shown capitalized for readability only.</em>  <em>Capslock should be off.</em></p>

<h2>SPECIAL CHARS</h2>
<table>
<thead>
<tr>
<th>Key/Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>Option+Ñ</td>
<td>Generates the "~" special Character.</td>
</tr></tbody></table>
 

<h2><a id="user-content-shortcuts" class="anchor" aria-hidden="true" href="#shortcuts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>SHORTCUTS</h2>
<table>
<thead>
<tr>
<th>Key/Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>Ctrl + A</td>
<td>Go to the beginning of the line you are currently typing on.  This also works for most text input fields system wide.  Netbeans being one exception</td>
</tr>
<tr>
<td>Ctrl + E</td>
<td>Go to the end of the line you are currently typing on.  This also works for most text input fields system wide.  Netbeans being one exception</td>
</tr>
<tr>
<td>Ctrl + Q</td>
<td>Clears everything on current line</td>
</tr>
<tr>
<td>Ctrl + L</td>
<td>Clears the Screen</td>
</tr>
<tr>
<td>Cmd + K</td>
<td>Clears the Screen</td>
</tr>
<tr>
<td>Ctrl + U</td>
<td>Cut everything backwards to beginning of line</td>
</tr>
<tr>
<td>Ctrl + K</td>
<td>Cut everything forward to end of line</td>
</tr>
<tr>
<td>Ctrl + W</td>
<td>Cut one word backwards using white space as delimiter</td>
</tr>
<tr>
<td>Ctrl + Y</td>
<td>Paste whatever was cut by the last cut command</td>
</tr>
<tr>
<td>Ctrl + H</td>
<td>Same as backspace</td>
</tr>
<tr>
<td>Ctrl + C</td>
<td>Kill whatever you are running</td>
</tr>
<tr>
<td>Ctrl + D</td>
<td>Exit the current shell when no process is running, or send EOF to a the running process</td>
</tr>
<tr>
<td>Ctrl + Z</td>
<td>Puts whatever you are running into a suspended background process. fg restores it.</td>
</tr>
<tr>
<td>Ctrl + _</td>
<td>Undo the last command. (Underscore.  So it's actually Ctrl + Shift + minus)</td>
</tr>
<tr>
<td>Ctrl + T</td>
<td>Swap the last two characters before the cursor</td>
</tr>
<tr>
<td>Ctrl + F</td>
<td>Move cursor one character forward</td>
</tr>
<tr>
<td>Ctrl + B</td>
<td>Move cursor one character backward</td>
</tr>
<tr>
<td>Option + →</td>
<td>Move cursor one word forward</td>
</tr>
<tr>
<td>Option + ←</td>
<td>Move cursor one word backward</td>
</tr>
<tr>
<td>Esc + T</td>
<td>Swap the last two words before the cursor</td>
</tr>
<tr>
<td>Tab</td>
<td>Auto-complete files and folder names</td>
</tr></tbody></table>
<h2><a id="user-content-core-commands" class="anchor" aria-hidden="true" href="#core-commands"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>CORE COMMANDS</h2>
<table>
<thead>
<tr>
<th>Key/Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>cd [folder]</td>
<td>Change directory e.g. <code>cd Documents</code></td>
</tr>
<tr>
<td>cd</td>
<td>Home directory</td>
</tr>
<tr>
<td>cd ~</td>
<td>Home directory</td>
</tr>
<tr>
<td>cd /</td>
<td>Root of drive</td>
</tr>
<tr>
<td>cd -</td>
<td>Previous directory</td>
</tr>
<tr>
<td>ls</td>
<td>Short listing</td>
</tr>
<tr>
<td>ls -l</td>
<td>Long listing</td>
</tr>
<tr>
<td>ls -a</td>
<td>Listing incl. hidden files</td>
</tr>
<tr>
<td>ls -lh</td>
<td>Long listing with Human readable file sizes</td>
</tr>
<tr>
<td>ls -R</td>
<td>Entire content of folder recursively</td>
</tr>
<tr>
<td>sudo [command]</td>
<td>Run command with the security privileges of the superuser (Super User DO)</td>
</tr>
<tr>
<td>open [file]</td>
<td>Opens a file ( as if you double clicked it )</td>
</tr>
<tr>
<td>top</td>
<td>Displays active processes. Press q to quit</td>
</tr>
<tr>
<td>nano [file]</td>
<td>Opens the file using the nano editor</td>
</tr>
<tr>
<td>vim [file]</td>
<td>Opens the file using the vim editor</td>
</tr>
<tr>
<td>clear</td>
<td>Clears the screen</td>
</tr>
<tr>
<td>reset</td>
<td>Resets the terminal display</td>
</tr></tbody></table>
<h2><a id="user-content-chaining-commands" class="anchor" aria-hidden="true" href="#chaining-commands"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>CHAINING COMMANDS</h2>
<table>
<thead>
<tr>
<th>Key/Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>[command-a]; [command-b]</td>
<td>Run command A and then B, regardless of success of A</td>
</tr>
<tr>
<td>[command-a] &amp;&amp; [command-b]</td>
<td>Run command B if A succeeded</td>
</tr>
<tr>
<td>[command-a] || [command-b]</td>
<td>Run command B if A failed</td>
</tr>
<tr>
<td>[command-a] &amp;</td>
<td>Run command A in background</td>
</tr></tbody></table>
<h2><a id="user-content-piping-commands" class="anchor" aria-hidden="true" href="#piping-commands"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>PIPING COMMANDS</h2>
<table>
<thead>
<tr>
<th>Key/Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>[command-a] | [command-b]</td>
<td>Run command A and then pass the result to command B e.g ps auxwww | grep google</td>
</tr></tbody></table>
<h2><a id="user-content-command-history" class="anchor" aria-hidden="true" href="#command-history"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>COMMAND HISTORY</h2>
<table>
<thead>
<tr>
<th>Key/Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>history n</td>
<td>Shows the stuff typed – add a number to limit the last n items</td>
</tr>
<tr>
<td>Ctrl + r</td>
<td>Interactively search through previously typed commands</td>
</tr>
<tr>
<td>![value]</td>
<td>Execute the last command typed that starts with ‘value’</td>
</tr>
<tr>
<td>![value]:p</td>
<td>Print to the console the last command typed that starts with ‘value’</td>
</tr>
<tr>
<td>!!</td>
<td>Execute the last command typed</td>
</tr>
<tr>
<td>!!:p</td>
<td>Print to the console the last command typed</td>
</tr></tbody></table>
<h2><a id="user-content-file-management" class="anchor" aria-hidden="true" href="#file-management"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>FILE MANAGEMENT</h2>
<table>
<thead>
<tr>
<th>Key/Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>touch [file]</td>
<td>Create a new file</td>
</tr>
<tr>
<td>pwd</td>
<td>Full path to working directory</td>
</tr>
<tr>
<td>.</td>
<td>Current folder, e.g. <code>ls .</code></td>
</tr>
<tr>
<td>..</td>
<td>Parent/enclosing directory, e.g. <code>ls ..</code></td>
</tr>
<tr>
<td>ls -l ..</td>
<td>Long listing of parent directory</td>
</tr>
<tr>
<td>cd ../../</td>
<td>Move 2 levels up</td>
</tr>
<tr>
<td>cat</td>
<td>Concatenate to screen</td>
</tr>
<tr>
<td>rm [file]</td>
<td>Remove a file, e.g. <code>rm data.tmp</code></td>
</tr>
<tr>
<td>rm -i [file]</td>
<td>Remove with confirmation</td>
</tr>
<tr>
<td>rm -r [dir]</td>
<td>Remove a directory and contents</td>
</tr>
<tr>
<td>rm -f [file]</td>
<td>Force removal without confirmation</td>
</tr>
<tr>
<td>cp [file] [newfile]</td>
<td>Copy file to file</td>
</tr>
<tr>
<td>cp [file] [dir]</td>
<td>Copy file to directory</td>
</tr>
<tr>
<td>mv [file] [new filename]</td>
<td>Move/Rename, e.g. <code>mv file1.ad /tmp</code></td>
</tr>
<tr>
<td>pbcopy &lt; [file]</td>
<td>Copies file contents to clipboard</td>
</tr>
<tr>
<td>pbpaste</td>
<td>Paste clipboard contents</td>
</tr>
<tr>
<td>pbpaste &gt; [file]</td>
<td>Paste clipboard contents into file, <code>pbpaste &gt; paste-test.txt</code></td>
</tr></tbody></table>
<h2><a id="user-content-directory-management" class="anchor" aria-hidden="true" href="#directory-management"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>DIRECTORY MANAGEMENT</h2>
<table>
<thead>
<tr>
<th>Key/Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>mkdir [dir]</td>
<td>Create new directory</td>
</tr>
<tr>
<td>mkdir -p [dir]/[dir]</td>
<td>Create nested directories</td>
</tr>
<tr>
<td>rmdir [dir]</td>
<td>Remove directory ( only operates on empty directories )</td>
</tr>
<tr>
<td>rm -R [dir]</td>
<td>Remove directory and contents</td>
</tr>
<tr>
<td>less [file]</td>
<td>Output file content delivered in screensize chunks</td>
</tr>
<tr>
<td>[command] &gt; [file]</td>
<td>Push output to file, keep in mind it will get overwritten</td>
</tr>
<tr>
<td>[command] &gt;&gt; [file]</td>
<td>Append output to existing file</td>
</tr>
<tr>
<td>[command] &lt; [file]</td>
<td>Tell command to read content from a file</td>
</tr></tbody></table>
<h2><a id="user-content-search" class="anchor" aria-hidden="true" href="#search"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>SEARCH</h2>
<table>
<thead>
<tr>
<th>Key/Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>find [dir] -name [search_pattern]</td>
<td>Search for files, e.g. <code>find /Users -name "file.txt"</code></td>
</tr>
<tr>
<td>grep [search_pattern] [file]</td>
<td>Search for all lines that contain the pattern, e.g. <code>grep "Tom" file.txt</code></td>
</tr>
<tr>
<td>grep -r [search_pattern] [dir]</td>
<td>Recursively search in all files in specified directory for all lines that contain the pattern</td>
</tr>
<tr>
<td>grep -v [search_pattern] [file]</td>
<td>Search for all lines that do NOT contain the pattern</td>
</tr>
<tr>
<td>grep -i [search_pattern] [file]</td>
<td>Search for all lines that contain the case-insensitive pattern</td>
</tr>
<tr>
<td>mdfind [search_pattern]</td>
<td>Spotlight search for files (names, content, other metadata), e.g. <code>mdfind skateboard</code></td>
</tr>
<tr>
<td>mdfind -onlyin [dir] -name [pattern]</td>
<td>Spotlight search for files named like pattern in the given directory</td>
</tr></tbody></table>
<h2><a id="user-content-help" class="anchor" aria-hidden="true" href="#help"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>HELP</h2>
<table>
<thead>
<tr>
<th>Key/Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>[command] -h</td>
<td>Offers help</td>
</tr>
<tr>
<td>[command] --help</td>
<td>Offers help</td>
</tr>
<tr>
<td>info [command]</td>
<td>Offers help</td>
</tr>
<tr>
<td>man [command]</td>
<td>Show the help manual for [command]</td>
</tr>
<tr>
<td>whatis [command]</td>
<td>Gives a one-line description of [command]</td>
</tr>
<tr>
<td>apropos [search-pattern]</td>
<td>Searches for command with keywords in description</td>
</tr></tbody></table>
</article>
