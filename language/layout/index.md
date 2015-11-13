# layout

{% craftml %}
<craft>
  <cube size="10 10 50"></cube>
  <cube size="10 50 10"></cube>
  <cube size="50 10 10"></cube>
</craft>
{% endcraftml %}

{% craftml %}
<craft>
  <g l="lineupX() centerY() alignZ(100%)">
    <cube size="10 10 50"></cube>
    <cube size="10 50 10"></cube>
    <cube size="50 10 10"></cube>
  </g>
</craft>
{% endcraftml %}