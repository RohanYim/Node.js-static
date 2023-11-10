# CSE330

Node.js is a JavaScript runtime environment that runs server-side, while PHP is a server-side scripting language. node.js does not natively support PHP scripts, and therefore cannot execute them directly. If you try to load phpinfo.php through Node.js, it will most likely only return the contents of the file as plain text, rather than executing the PHP code and generating the expected output. This is because Node.js does not recognize PHP code as executable code.
