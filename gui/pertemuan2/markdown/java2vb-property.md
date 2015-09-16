<p>Goodbye Getter &amp; Setter, Welcome Property</p>

<p class="fragment">From</p>
<pre><code class="fragment">
private String name;
public String getName() {
  return name;
}
public void setName(String name) {
  this.name = name;
}
</code></pre>

<p class="fragment">Into</p>
<pre><code class="fragment">
Dim name As String
Property Name() As String
  Get
    Return name
  End Get
  Set(ByVal value As String)
    name = value
  End Set
End Property
</code></pre>
