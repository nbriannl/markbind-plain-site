<frontmatter>
  header: header.md
  pageNav: 2
  pageNavTitle: "Chapters of This Page"
  siteNav: site-nav.md
</frontmatter>

<br>

# Testing no-icon, no-background, no-border

## positive attributes override presence of negative

```
<box no-background background-color="yellow">
    Lorem ipsum dolor sit amet,
</box>

<box no-border border-color="grey">
    Lorem ipsum dolor sit amet,
</box>

<box no-border border-left-color="grey">
    Lorem ipsum dolor sit amet,
</box>

<box no-icon icon=":fas-camera:" >
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>

<box no-icon type="info" icon=":rocket:">
    info
</box>

<box no-icon type="info" icon="">
    info
</box>

```

<box no-background background-color="yellow">
    Lorem ipsum dolor sit amet,
</box>

<box no-border border-color="grey">
    Lorem ipsum dolor sit amet,
</box>

<box no-border border-left-color="grey">
    Lorem ipsum dolor sit amet,
</box>

<box no-icon icon=":fas-camera:" >
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>

<box no-icon type="info" icon=":rocket:">
    info
</box>

<box no-icon type="info" icon="">
    info
</box>

## Default boxes
<box>
    default
</box>

<box type="info">
    info
</box>

<box type="warning">
    warning
</box>

<box type="success">
    success
</box>

<box type="important">
    important
</box>

<box type="wrong">
    wrong
</box>

<box type="tip">
    tip
</box>

<box type="definition">
    definition
</box>

<box type="info" dismissible>
    dismissible info
</box>

<box type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box type="info" light>
    info light
</box>
<box type="warning" light>
    warning light
</box>
<box type="success" light>
    success light
</box>
<box type="important" light>
    important light
</box>
<box type="wrong" light>
    wrong light
</box>
<box type="tip" light>
    tip light
</box>
<box type="definition" light>
    definition light
</box>

<box seamless>
    info seamless
</box>
<box type="info" seamless>
    info seamless
</box>
<box type="warning" seamless>
    warning seamless
</box>
<box type="success" seamless>
    success seamless
</box>
<box type="important" seamless>
    important seamless
</box>
<box type="wrong" seamless>
    wrong seamless
</box>
<box type="tip" seamless>
    tip seamless
</box>
<box type="definition" seamless>
    definition seamless
</box>

<box background-color="white" border-color="grey" border-left-color="blue">
    default, styled as empty box with blue left border
</box>
<box type="info" icon=":rocket:">
    info, with rocket icon
</box>

<box type="warning" icon=":fas-camera:">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box type="warning" icon=":fas-camera:" icon-size="2x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box type="warning" icon=":fas-camera:" icon-size="3x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>

## no-icon 
<box no-icon>
    default
</box>

<box no-icon type="info">
    info
</box>

<box no-icon type="warning">
    warning
</box>

<box no-icon type="success">
    success
</box>

<box no-icon type="important">
    important
</box>

<box no-icon type="wrong">
    wrong
</box>

<box no-icon type="tip">
    tip
</box>

<box no-icon type="definition">
    definition
</box>

<box no-icon type="info" dismissible>
    dismissible info
</box>

<box no-icon type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box no-icon type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box no-icon type="info" light>
    info light
</box>
<box no-icon type="warning" light>
    warning light
</box>
<box no-icon type="success" light>
    success light
</box>
<box no-icon type="important" light>
    important light
</box>
<box no-icon type="wrong" light>
    wrong light
</box>
<box no-icon type="tip" light>
    tip light
</box>
<box no-icon type="definition" light>
    definition light
</box>

<box no-icon seamless>
    info seamless
</box>
<box no-icon type="info" seamless>
    info seamless
</box>
<box no-icon type="warning" seamless>
    warning seamless
</box>
<box no-icon type="success" seamless>
    success seamless
</box>
<box no-icon type="important" seamless>
    important seamless
</box>
<box no-icon type="wrong" seamless>
    wrong seamless
</box>
<box no-icon type="tip" seamless>
    tip seamless
</box>
<box no-icon type="definition" seamless>
    definition seamless
</box>

<box no-icon background-color="white" border-color="grey" border-left-color="blue">
    default, styled as empty box with blue left border
</box>
<box no-icon type="info" icon=":rocket:">
    info, with rocket icon
</box>

<box no-icon type="warning" icon=":fas-camera:">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box no-icon type="warning" icon=":fas-camera:" icon-size="2x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box no-icon type="warning" icon=":fas-camera:" icon-size="3x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>

## no-background 
<box no-background>
    default
</box>

<box no-background type="info">
    info
</box>

<box no-background type="warning">
    warning
</box>

<box no-background type="success">
    success
</box>

<box no-background type="important">
    important
</box>

<box no-background type="wrong">
    wrong
</box>

<box no-background type="tip">
    tip
</box>

<box no-background type="definition">
    definition
</box>

<box no-background type="info" dismissible>
    dismissible info
</box>

<box no-background type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box no-background type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box no-background type="info" light>
    info light
</box>
<box no-background type="warning" light>
    warning light
</box>
<box no-background type="success" light>
    success light
</box>
<box no-background type="important" light>
    important light
</box>
<box no-background type="wrong" light>
    wrong light
</box>
<box no-background type="tip" light>
    tip light
</box>
<box no-background type="definition" light>
    definition light
</box>

<box no-background seamless>
    info seamless
</box>
<box no-background type="info" seamless>
    info seamless
</box>
<box no-background type="warning" seamless>
    warning seamless
</box>
<box no-background type="success" seamless>
    success seamless
</box>
<box no-background type="important" seamless>
    important seamless
</box>
<box no-background type="wrong" seamless>
    wrong seamless
</box>
<box no-background type="tip" seamless>
    tip seamless
</box>
<box no-background type="definition" seamless>
    definition seamless
</box>

<box no-background background-color="white" border-color="grey" border-left-color="blue">
    default, styled as empty box with blue left border
</box>
<box no-background type="info" icon=":rocket:">
    info, with rocket icon
</box>

<box no-background type="warning" icon=":fas-camera:">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box no-background type="warning" icon=":fas-camera:" icon-size="2x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box no-background type="warning" icon=":fas-camera:" icon-size="3x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>

## no-border 
<box no-border>
    default
</box>

<box no-border type="info">
    info
</box>

<box no-border type="warning">
    warning
</box>

<box no-border type="success">
    success
</box>

<box no-border type="important">
    important
</box>

<box no-border type="wrong">
    wrong
</box>

<box no-border type="tip">
    tip
</box>

<box no-border type="definition">
    definition
</box>

<box no-border type="info" dismissible>
    dismissible info
</box>

<box no-border type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box no-border type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box no-border type="info" light>
    info light
</box>
<box no-border type="warning" light>
    warning light
</box>
<box no-border type="success" light>
    success light
</box>
<box no-border type="important" light>
    important light
</box>
<box no-border type="wrong" light>
    wrong light
</box>
<box no-border type="tip" light>
    tip light
</box>
<box no-border type="definition" light>
    definition light
</box>

<box no-border seamless>
    info seamless
</box>
<box no-border type="info" seamless>
    info seamless
</box>
<box no-border type="warning" seamless>
    warning seamless
</box>
<box no-border type="success" seamless>
    success seamless
</box>
<box no-border type="important" seamless>
    important seamless
</box>
<box no-border type="wrong" seamless>
    wrong seamless
</box>
<box no-border type="tip" seamless>
    tip seamless
</box>
<box no-border type="definition" seamless>
    definition seamless
</box>

<box no-border background-color="white" border-color="grey" border-left-color="blue">
    default, styled as empty box with blue left border
</box>
<box no-border type="info" icon=":rocket:">
    info, with rocket icon
</box>

<box no-border type="warning" icon=":fas-camera:">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box no-border type="warning" icon=":fas-camera:" icon-size="2x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box no-border type="warning" icon=":fas-camera:" icon-size="3x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>

## no-background no-border 
<box no-background no-border>
    default
</box>

<box no-background no-border type="info">
    info
</box>

<box no-background no-border type="warning">
    warning
</box>

<box no-background no-border type="success">
    success
</box>

<box no-background no-border type="important">
    important
</box>

<box no-background no-border type="wrong">
    wrong
</box>

<box no-background no-border type="tip">
    tip
</box>

<box no-background no-border type="definition">
    definition
</box>

<box no-background no-border type="info" dismissible>
    dismissible info
</box>

<box no-background no-border type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box no-background no-border type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box no-background no-border type="info" light>
    info light
</box>
<box no-background no-border type="warning" light>
    warning light
</box>
<box no-background no-border type="success" light>
    success light
</box>
<box no-background no-border type="important" light>
    important light
</box>
<box no-background no-border type="wrong" light>
    wrong light
</box>
<box no-background no-border type="tip" light>
    tip light
</box>
<box no-background no-border type="definition" light>
    definition light
</box>

<box no-background no-border seamless>
    info seamless
</box>
<box no-background no-border type="info" seamless>
    info seamless
</box>
<box no-background no-border type="warning" seamless>
    warning seamless
</box>
<box no-background no-border type="success" seamless>
    success seamless
</box>
<box no-background no-border type="important" seamless>
    important seamless
</box>
<box no-background no-border type="wrong" seamless>
    wrong seamless
</box>
<box no-background no-border type="tip" seamless>
    tip seamless
</box>
<box no-background no-border type="definition" seamless>
    definition seamless
</box>

<box no-background no-border background-color="white" border-color="grey" border-left-color="blue">
    default, styled as empty box with blue left border
</box>

<box no-background no-border type="info" icon=":rocket:">
    info, with rocket icon
</box>

<box no-background no-border type="warning" icon=":fas-camera:">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box no-background no-border type="warning" icon=":fas-camera:" icon-size="2x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box no-background no-border type="warning" icon=":fas-camera:" icon-size="3x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>

## no-background no-icon 
<box no-background no-icon>
    default
</box>

<box no-background no-icon type="info">
    info
</box>

<box no-background no-icon type="warning">
    warning
</box>

<box no-background no-icon type="success">
    success
</box>

<box no-background no-icon type="important">
    important
</box>

<box no-background no-icon type="wrong">
    wrong
</box>

<box no-background no-icon type="tip">
    tip
</box>

<box no-background no-icon type="definition">
    definition
</box>

<box no-background no-icon type="info" dismissible>
    dismissible info
</box>

<box no-background no-icon type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box no-background no-icon type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box no-background no-icon type="info" light>
    info light
</box>
<box no-background no-icon type="warning" light>
    warning light
</box>
<box no-background no-icon type="success" light>
    success light
</box>
<box no-background no-icon type="important" light>
    important light
</box>
<box no-background no-icon type="wrong" light>
    wrong light
</box>
<box no-background no-icon type="tip" light>
    tip light
</box>
<box no-background no-icon type="definition" light>
    definition light
</box>

<box no-background no-icon seamless>
    info seamless
</box>
<box no-background no-icon type="info" seamless>
    info seamless
</box>
<box no-background no-icon type="warning" seamless>
    warning seamless
</box>
<box no-background no-icon type="success" seamless>
    success seamless
</box>
<box no-background no-icon type="important" seamless>
    important seamless
</box>
<box no-background no-icon type="wrong" seamless>
    wrong seamless
</box>
<box no-background no-icon type="tip" seamless>
    tip seamless
</box>
<box no-background no-icon type="definition" seamless>
    definition seamless
</box>

<box no-background no-icon background-color="white" border-color="grey" border-left-color="blue">
    default, styled as empty box with blue left border
</box>
<box no-background no-icon type="info" icon=":rocket:">
    info, with rocket icon
</box>

<box no-background no-icon type="warning" icon=":fas-camera:">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box no-background no-icon type="warning" icon=":fas-camera:" icon-size="2x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box no-background no-icon type="warning" icon=":fas-camera:" icon-size="3x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>

## no-icon no-border 
<box no-icon no-border>
    default
</box>

<box no-icon no-border type="info">
    info
</box>

<box no-icon no-border type="warning">
    warning
</box>

<box no-icon no-border type="success">
    success
</box>

<box no-icon no-border type="important">
    important
</box>

<box no-icon no-border type="wrong">
    wrong
</box>

<box no-icon no-border type="tip">
    tip
</box>

<box no-icon no-border type="definition">
    definition
</box>

<box no-icon no-border type="info" dismissible>
    dismissible info
</box>

<box no-icon no-border type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box type="success" header="Tip box header">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    <box no-icon no-border type="warning" header="Tip box header" dismissible>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </box>
</box>

<box no-icon no-border type="info" light>
    info light
</box>
<box no-icon no-border type="warning" light>
    warning light
</box>
<box no-icon no-border type="success" light>
    success light
</box>
<box no-icon no-border type="important" light>
    important light
</box>
<box no-icon no-border type="wrong" light>
    wrong light
</box>
<box no-icon no-border type="tip" light>
    tip light
</box>
<box no-icon no-border type="definition" light>
    definition light
</box>

<box no-icon no-border seamless>
    info seamless
</box>
<box no-icon no-border type="info" seamless>
    info seamless
</box>
<box no-icon no-border type="warning" seamless>
    warning seamless
</box>
<box no-icon no-border type="success" seamless>
    success seamless
</box>
<box no-icon no-border type="important" seamless>
    important seamless
</box>
<box no-icon no-border type="wrong" seamless>
    wrong seamless
</box>
<box no-icon no-border type="tip" seamless>
    tip seamless
</box>
<box no-icon no-border type="definition" seamless>
    definition seamless
</box>

<box no-icon no-border background-color="white" border-color="grey" border-left-color="blue">
    default, styled as empty box with blue left border
</box>
<box no-icon no-border type="info" icon=":rocket:">
    info, with rocket icon
</box>

<box no-icon no-border type="warning" icon=":fas-camera:">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box no-icon no-border type="warning" icon=":fas-camera:" icon-size="2x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>
<box no-icon no-border type="warning" icon=":fas-camera:" icon-size="3x">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</box>