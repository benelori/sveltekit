<script>
  import { Meta, Template, Story } from "@storybook/addon-svelte-csf";
  import Button from "./Button.svelte";
</script>

<Meta
  title="Example/Button"
  component={Button}
  argTypes={{
    label: { control: "text" },
  }}
/>

<Template let:args>
  <Button {...args} />
</Template>

<Story
  name="Primary"
  args={{
    label: "Button",
  }}
/>

