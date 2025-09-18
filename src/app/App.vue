<script setup lang="ts">
import Form from "@/features/Form/ui/Form.vue";
import { Button } from "@/shared/api/ui/button";

import Container from "@/shared/ui/Container.vue";
</script>

<template>
  <Container>
    <div class="max-w-240">
      <div class="flex gap-8 items-center">
        <h1 class="font-bold text-2xl">Учетные записи</h1>
        <Button class="cursor-pointer">+</Button>
      </div>
      <div class="mt-4 p-4 bg-blue-50">
        <p>
          Для поля типа: <i><b>метка</b></i> можно указать несколько значений,
          используя разделитель ;
        </p>
      </div>

      <Form />
    </div>
  </Container>
</template>
