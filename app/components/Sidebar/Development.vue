<template>
  <LazySidebarSubmenu>
    <template #trigger>
      <UiButton
        ghost
        icon-name="lucide:ellipsis"
        :icon-only="true"
        title="More Features"
        circle
        tag="summary"
      />
    </template>
    <UiButton
      to="/assistants"
      ghost
      disabled
      icon-name="lucide:bot-message-square"
      :icon-only="true"
      title="Assistants (In development)"
      circle
      tooltip-position="bottom"
      tooltip-style="error"
    />
    <UiButton
      to="/workspaces"
      ghost
      disabled
      icon-name="lucide:layers-2"
      :icon-only="true"
      title="Workspaces (In development)"
      circle
      tooltip-position="bottom"
      tooltip-style="error"
    />
  </LazySidebarSubmenu>
</template>
