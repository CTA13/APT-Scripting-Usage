<h1>APT Script Usage</h1>

<h2>Overview</h2>
<p>The Purpose of this document is to show users how to manage application packages using the APT script (Advanced Packaging Tool) and Repoman functions in Pop!_OS. </p>

<h2>APT Scripts</h2>

<p>APT scripting can be used to execute many commands when managing applications in the terminal. These commands are crucial for software to be installed or updated so packages function properly. It provides the same functionality as specialized APT tools, like <code>apt get</code> and <code>apt cache</code>, but enables more configurable options.</p>

<p>Most commonly used commands:<p/>
<ol>
  <il><code>list</code> - list packages based on package names<br/>
  <il><code>search</code> - search in package descriptions<br/>
  <il><code>show</code> - show package details<br/>
  <il><code>install</code> - install packages<br/>
  <il><code>reinstall</code> - reinstall packages<br/>
  <il><code>remove</code> - remove packages<br/>
  <il><code>autoremove</code> - Remove automatically all unused packages<br/>
  <il><code>update</code> - update list of available packages<br/>
  <il><code>upgrade</code> - upgrade the system by installing/upgrading packages<br/>
  <il><code>full-upgrade</code> - upgrade the system by removing/installing/upgrading packages<br/>
  <il><code>edit-sources</code> - edit the source information file<br/>
  <il><code>satisfy</code> - satisfy dependency strings</il>
</ol>
<img src="https://media.giphy.com/media/jCctwYR7CHzcMLzdeE/giphy.gif"/>

<h2>Manually Manage Packages Using Repoman</h2>

<p>If a user is having issues executing the APT scripts, Repoman can be used to manually manage packages.<br /> To launch Repoman, type <code>repoman</code> into the terminal or by clicking the "Gear" button in the top right corner of the Pop!_Shop. Once Repoman is open, select the “Extra Sources” tab to start managing packages. Here, sources can be edited, added or deleted manually.</p>
<img src="https://media.giphy.com/media/ziX1LUwoiNGPHi6csE/giphy.gif"/>
