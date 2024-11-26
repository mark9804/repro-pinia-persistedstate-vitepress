---

---

# test pinia-persisted-plugin

<script setup lang="ts">
import { useStore } from './store.ts'

const store = useStore()
</script>

<div>{{ store.count }}</div>

<button style="border: 1px solid black; padding: 10px; border-radius: 4px;" @click="store.count++">increment</button>