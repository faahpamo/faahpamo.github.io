### Hello world!

This is the GitHub page of Faisal Ahmed Pasha Mohammed. I'm passionate about IT management, Java, Linux, TCP/IP, RDBMS and Mathematics. I enjoy programming because it's fun and creative.
    

### Articles
  * <a href="blog/todo-web-application-using-java-ee/">ToDo List Web Application Using Java EE</a>  [*<a href="https://github.com/faimoh/todowebapp">Source Code</a>*] <br />
  * <a href="blog/dao-design-pattern-in-java/">DAO Design Pattern in Java</a> [*<a href="https://github.com/faimoh/dao-design-pattern">Source Code</a>*] <br />
  * <a href="blog/mysql-how- to-obtain-last-insert-ID-for-an-AUTO_INCREMENT-column/">MySQL - How to obtain last insert ID for an AUTO_INCREMENT column?</a> <br/>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
