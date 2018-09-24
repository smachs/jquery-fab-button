# jQuery FAB Button

<a href="https://github.com/smachs/jquery-fab-button"><img  width="91px" height="93px" src="https://s3-sa-east-1.amazonaws.com/fujikawa-cloud-hosting/gabriel/work/open-source/design/jquery-fab-button/lifesaver.svg" align="left" align="left" hspace="10" vspace="6"></a>
A **small** module for **jQuery** and **Javascript** based in **MaterializeCSS** one day I was looking for some alternative to **floating action buttons** but with no result and the **floating action buttons** that I thought were either incomplete or not feasible I remembered that I used **MaterializeCSS** and I decided to adapt only the **floating action button** to be used separately from framework.

## Resources

* [API Reference](https://materializecss.com/floating-action-button.html)
* [Release Notes](https://github.com/smachs/jquery-fab-button/releases)
* [Gallery]()
* [Wiki](https://github.com/smachs/jquery-fab-button/wiki)

## Future Updates
* [ ] More animations.
* [ ] Tooltips.
* [ ] Modal generator.
* [ ] Badges with animations for notifications that are received.
* [ ] Color palette to be used directly in the FAB using data attributes.

## Table of Resources

* [Getting Started](#getting-started)

## Getting Started

1. Clone the repository using url

```bash
$ git clone https://github.com/smachs/jquery-fab-button
```

2. Copy all dependencies from directory

```bash
$ cd /js or /css
```

3. Add to your template

```bash
<!-- Add in HEAD -- >
<link href="../css/jquery-fab-button.css" rel="stylesheet">
<!-- Add After BODY -- >
<script src="../jss/jquery-fab-button.min.js"></script>
```

4. Change to color you want

```bash
.btn-floating {
    background-color: #3f51b5;
}
.btn-floating:hover {
    background-color: #3f51b5;
}
```

5. Add FAB to your template

```bash
<div class="fixed-action-btn horizontal" style="bottom: 45px; right: 24px;">
    <a class="btn-floating btn-large red">
        <i class="large material-icons">mode_edit</i>
    </a>
    <ul>
        <li>
            <a class="btn-floating bg-indigo">
                <i class="material-icons">insert_chart</i>
            </a>
        </li>
        <li>
            <a class="btn-floating bg-indigo">
                <i class="material-icons">format_quote</i>
            </a>
        </li>
        <li>
            <a class="btn-floating bg-indigo">
                <i class="material-icons">publish</i>
            </a>
        </li>
        <li>
            <a class="btn-floating bg-indigo">
                <i class="material-icons">attach_file</i>
            </a>
        </li>
    </ul>
</div>
```

### Contributing

Thanks for your interest in contributing! Read up on our guidelines for
[contributing](https://github.com/smachs/jquery-fab-button/blob/master/CONTRIBUTING.md)
and then look through our issues with a [help wanted](https://github.com/smachs/jquery-fab-button/issues?q=how-to-help-project)
label :yum:
