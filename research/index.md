---
title: Research
nav:
  order: 2
  tooltip: Our research and publications
---

<!---
---
title: Publications
nav:
  order: 2
  tooltip: Published works
---
-->

# {% include icon.html icon="fa-solid fa-microscope" %}Research
<!---
# {% include icon.html icon="fa-solid fa-microscope" %}Publications
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
-->

Our current research spans a wide spectrum of research topics, including:

<!---
- Software Security
  - General
  - Program Analysis
    - Binary Analysis
      - General
      - Heterogeneous Systems Binary Analysis
  - Program Testing
    - Fuzz Testing
      - General
      - Directed Fuzzing
- Hardware Security
  - Trusted Execution Environments
    - Remote Attestation
  - Hardware-Software Co-Design
- Machine Learning Security
  - General
  - Adversarial Examples
  - Machine Learning Systems
-->

<style>
.list {
  position: relative;
}
.list h2 {
  color: #fff;
  font-weight: 700;
  letter-spacing: 1px;
  margin-bottom: 10px;
}
.list ul {
  position: relative;
}
.list ul li {
  position: relative;
  left: 0;
  color: #fce4ec;
  list-style: none;
  margin: 4px 0;
  border-left: 2px solid #f50057;
  transition: 0.5s;
  cursor: pointer;
}
.list ul li:hover {
  left: 10px;
}
.list ul li span {
  position: relative;
  padding: 8px;
  padding-left: 12px;
  display: inline-block;
  z-index: 1;
  transition: 0.5s;
}
.list ul li:hover span {
  color: #111;
}
.list ul li:before {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  background: #f50057;
  transform: scaleX(0);
  transform-origin: left;
  transition: 0.5s;
}
.list ul li:hover:before {
  transform: scaleX(1);
}
</style>


<ul>
  <li style="color: #092312;">Software Security
    <ul>
      <li style="color: #0d351b;">General</li>
      <li style="color: #0d351b;">Program Analysis
        <ul>
          <li style="color: #0d351b;">Binary Analysis
            <ul>
              <li style="color: #0d351b;">General</li>
              <li style="color: #0d351b;">Heterogeneous Systems Binary Analysis</li>
            </ul>
          </li>
        </ul>
      </li>
    </ul>
    <ul>
      <li style="color: #0d351b;">Program Testing
        <ul>
          <li style="color: #0d351b;">Fuzz Testing
            <ul>
              <li style="color: #0d351b;">General</li>
              <li style="color: #0d351b;">Directed Fuzzing</li>
            </ul>
          </li>
        </ul>
      </li>
    </ul>
  </li>
  <li style="color: #092312;">Hardware Security
    <ul>
      <li style="color: #0d351b;">Trusted Execution Environments
        <ul>
          <li style="color: #0d351b;">Remote Attestation</li>
        </ul>
      </li>
      <li style="color: #0d351b;">Hardware-Software Co-Designs</li>
    </ul>
  </li>
  <li style="color: #092312;">Machine Learning Security
    <ul>
      <li style="color: #0d351b;">General</li>
      <li style="color: #0d351b;">Adversarial Examples</li>
      <li style="color: #0d351b;">Machine Learning Systems</li>
    </ul>
  </li>
</ul>

<ul>
  <li><span>Lorem ipsum dolor sit amet</span></li>
  <li><span>Consectetur adipisicing elit</span></li>
  <li><span>Ut labore et dolore magna aliqua</span></li>
  <li><span>Ut enim ad minim veniam</span></li>
  <li><span>Quis nostrud exercitation ullamco</span></li>
  <li><span>Laboris nisi ut aliquip ex</span></li>
</ul>

{% include section.html %}


<!---
## All
-->

## Publications

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
