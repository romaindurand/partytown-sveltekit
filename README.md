# partytown-sveltekit

A simple svelte wrapper for [@builder.io/partytown](https://partytown.builder.io/)

## Install

`npm i -D partytown-sveltekit`

## Setup

Partytown requires some scripts to be served by the app and provides a convinience script to achieve this.

### sveltekit

`npx @builder.io/partytown copylib static/~partytown`

### svelte

`npx @builder.io/partytown copylib public/~partytown`

## Usage

- In your layout :
```html
<script>
    import PartytownSnippet from 'partytown-sveltekit/PartytownSnippet.svelte'
</script>

<PartytownSnippet />
```

- To include a third-party script :
```html
<script>
    import Partytown from 'partytown-sveltekit/Partytown.svelte'
</script>

<Partytown script="<INLINE THIRD-PARTY SCRIPT>">
```

