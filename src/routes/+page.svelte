<script>
  import { Tabs } from 'bits-ui';
</script>

<Tabs.Root value="home">
  <Tabs.List>
    <Tabs.Trigger value="home">
      Home
    </Tabs.Trigger>

    <Tabs.Trigger value="vessels">
      Vessels
    </Tabs.Trigger>

    <Tabs.Trigger value="weapons">
      Weapons
    </Tabs.Trigger>
  </Tabs.List>

  <Tabs.Content value="home">
    Home
  </Tabs.Content>

  <Tabs.Content value="vessels">
    Vessels
  </Tabs.Content>

  <Tabs.Content value="weapons">
    Weapons
  </Tabs.Content>
</Tabs.Root>
