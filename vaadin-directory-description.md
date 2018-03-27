# Simple timeline component for Polymer 1

[![Available in Vaadin_Directory](https://img.shields.io/vaadin-directory/v/vaadinvaadin-grid.svg)](https://vaadin.com/directory/components/samiesimple-timeline)

With simple-timeline you can present a horizontal timeline of events. The event are relative left is 0 and right is 100 and vertically the titles can be set on different levels (-3 to 3). A custom item click listener can be added to make the timeline diagram interactive.

Version v1.x is targeted for Polymer 1, and v2.x is targeted for Polymer 2.

## Example usage:
```
<simple-timeline id="mytimeline" breaks="0=Q1/2018;25=Q2;50=Q3;75=Q4 (and we should be ready)">
    <simple-timeline-item id="today" x="16" y="3">Today</simple-timeline-item>
    <simple-timeline-item x="10" y="-1">Project start</simple-timeline-item>
    <simple-timeline-item x="20" y="-2">Prototypes ready. Start collecting feedback.</simple-timeline-item>
    <simple-timeline-item class="release" x="30" y="1">Alpha1 release</simple-timeline-item>
    <simple-timeline-item class="release" x="52" y="1">Beta1 release</simple-timeline-item>
    <simple-timeline-item x="75" y="2">RC release</simple-timeline-item>
    <simple-timeline-item id="final-release" x="85" y="3">Release Date</simple-timeline-item>
</simple-timeline>
```

<!-- DEMO: http://samie.github.io/simple-timeline/ -->
<!-- DOCS: N/A -->


