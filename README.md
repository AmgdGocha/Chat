<h1>Chat</h1>
CS470 Project 1 - Peer-to-peer chat application using socket programming in Java.

<h2>Notes</h2>
When changing Java source code, .jar file needs to be recompiled if running the program from terminal. Consult specific IDE for more instructions, making sure to include the json.jar file in the libs folder.

<h2>Running the program</h2>
<ul>
  <li>
    <ol>
      <h3>Terminal</h3>
      <li><code>cd Chat</code></li>
      <li><code>java -jar chat.jar</code></li>
    </ol>
  </li>
   <li>
    <ol>
      <h3>Eclipse</h3>
      <li>Run Chat.java as Java Application</li>
    </ol>
  </li>
</ul>

<h2>After running the program</h2>
<code>chat \<port no.\></code>, e.g. <code>chat 4000</code>

<h2>Usage</h2>
1) <code>help</code>- Displays list of available commands and their usages.

2) <code>myip</code>- Display user IP address.

3) <code>myport</code>- Display user port number.

4) <code>connect</code>-
  <ul>
    <li>Establish connection with {destination IP}  using {port number}.</li>
    <li><code>connect [destination IP] [port number]</code></li>
    <li>Example: <code>connect 192.168.1.151 6000</code></li>
  </ul>

5) <code>list</code>- Display list of peers connected.

6) <code>terminate</code>-
 <ul>
    <li>Terminate the connection with a specific address.</li>
    <li><code>terminate [connection id]</code></li>
    <li>Example: <code>terminate 1</code></li>
  </ul>

7) <code>send</code>-
 <ul>
    <li>Send a message to a peer with the specific ID.</li>
    <li><code>send [peer id] [message]</code></li>
    <li>Example: <code>send 1 hello world</code></li>
  </ul>

8) <code>exit</code>- Close all connections and terminate the program.


