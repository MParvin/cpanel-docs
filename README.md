## Welcome to GitHub Pages

<h2>cPanel logs</h2>
<table class="article_table">
  <tbody>
    
<tr>
<th style="width: 65%; padding: 5px;">Access logs and user actions</th>
  <td style="padding: 5px;">/usr/local/cpanel/logs/access_log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Account transfers and misc. logs</th>
<td style="padding: 5px;">/var/cpanel/logs</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Auditing log (account creations, deletions, etc)</th>
<td style="padding: 5px;">/var/cpanel/accounting.log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Backup logs</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/cpbackup</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Brute force protection (cphulkd) log</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/cphulkd.log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Cpanel dnsadmin dns clustering daemon</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/dnsadmin_log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Cpanel taskqueue processing daemon</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/queueprocd.log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">DBmapping</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/setupdbmap_log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">EasyApache build logs</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/easy/apache/</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Error log</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/error_log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Installation log</th>
<td style="padding: 5px;">/var/log/cpanel</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">License updates and errors</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/license_log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Locale database modifications</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/build_locale_database_log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Login errors (CPSRVD)</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/login_log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Horde</th>
<td style="padding: 5px;">/var/cpanel/horde/log/</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">RoundCube</th>
<td style="padding: 5px;">/var/cpanel/roundcube/log/</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">SquirrelMail</th>
<td style="padding: 5px;">/var/cpanel/squirrelmail/</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Panic log</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/panic_log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Per account bandwidth history (Cached)</th>
<td style="padding: 5px;">/var/cpanel/bandwidth.cache/{USERNAME}</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Per account bandwidth history (Human Readable)</th>
<td style="padding: 5px;">/var/cpanel/bandwidth/{USERNAME}</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Service status logs</th>
<td style="padding: 5px;">/var/log/chkservd.log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Tailwatch driver tailwatchd log</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/tailwatch_log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Update analysis reporting</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/updated_analysis/{TIMESTAMP}.log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Update (UPCP) log</th>
<td style="padding: 5px;">/var/cpanel/updatelogs/updated.{TIMESTAMP}.log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">WebDisk (CPDAVD)</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/cpdavd_error_log</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">Website statistics log</th>
<td style="padding: 5px;">/usr/local/cpanel/logs/stats_log</td>
</tr>

  </tbody>
  </table>
  
  
  <h2>cPanel access log</h2>
  
  <table class="article_table">
  <tbody>
    
<tr>
<th style="width: 65%; padding: 5px;">Access logs and user actions</th>
  <td style="padding: 5px;">/usr/local/cpanel/logs/access_log</td>
</tr>
  </tbody>
  </table>
  
  <h2>cPanel apache log</h2>
  <table class="article_table">
  <tbody>
    
<tr>
<th style="width: 65%; padding: 5px;">Apache restarts done through cPanel and WHM</th>
  <td style="padding: 5px;">/usr/local/cpanel/logs/safeapcherestart_log</td>
</tr>
    
    <tr>
<th style="width: 65%; padding: 5px;">Domain access logs</th>
      <td style="padding: 5px;">/usr/local/apache/domlogs/{DOMAIN}</td>
</tr>
    
    <tr>
<th style="width: 65%; padding: 5px;">Processing of log splitting</th>
      <td style="padding: 5px;">/usr/local/cpanel/logs/splitlogs_log</td>
</tr>
    
    <tr>
<th style="width: 65%; padding: 5px;">suPHP audit log</th>
      <td style="padding: 5px;">/usr/local/apache/logs/suphp_log</td>
</tr>
    
    <tr>
<th style="width: 65%; padding: 5px;">Web server and CGI application error log</th>
      <td style="padding: 5px;">/usr/local/apache/logs/error_log</td>
</tr>
    
    
  </tbody>
  </table>
  
  <h2>cPanel email log</h2>
  
  <table class="article_table">
  <tbody>
    
<tr>
<th style="width: 65%; padding: 5px;">Delivery and receipt log</th>
  <td style="padding: 5px;">/var/log/exim_mainlog</td>
</tr>
    
    <tr>
<th style="width: 65%; padding: 5px;">Incoming mail queue</th>
      <td style="padding: 5px;">/var/spool/exim/input/</td>
</tr>
    
    <tr>
<th style="width: 65%; padding: 5px;">Log of messages rejected based on ACLS or other policies</th>
      <td style="padding: 5px;">/var/log/exim_rejectlog</td>
</tr>
    
    <tr>
      <th style="width: 65%; padding: 5px;">Unexpected/Fatal error log</th>
      <td style="padding: 5px;">/var/log/exim_paniclog</td>
</tr>
    
    <tr>
<th style="width: 65%; padding: 5px;">IMAP, POP login attempts, transactions, fatal errors and spam scoring</th>
      <td style="padding: 5px;">/var/log/maillog</td>
      <td style="padding: 5px;">/var/log/messages</td>
</tr>
    
    <tr>
<th style="width: 65%; padding: 5px;">Mailman</th>
      <td style="padding: 5px;">/usr/local/cpanel/3rdparty/mailmain/logs</td>
</tr>    
    
  </tbody>
  </table>
  
  <h2>MySQL log</h2>
  <table class="article_table">
  <tbody>
    
<tr>
<th style="width: 65%; padding: 5px;">MySQL error log</th>
  <td style="padding: 5px;">/var/lib/mysql/{SERVER_NAME}.err</td>
</tr>
<tr>
<th style="width: 65%; padding: 5px;">MySQL slow query log (if enabled in my.cnf)</th>
  <td style="padding: 5px;">/var/log/slowqueries</td>
</tr>
      
  </tbody>
</table>
