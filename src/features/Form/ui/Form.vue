<script lang="ts" setup>
import { Input } from "@/shared/api/ui/input";

import {
  Select,
  SelectContent,
  SelectGroup,
  SelectItem,
  SelectTrigger,
  SelectValue,
} from "@/shared/api/ui/select";
</script>

<template>
  <form class="mt-5">
    <table class="w-full">
      <thead>
        <tr class="text-left font-normal">
          <th>Метки</th>
          <th>Тип записи</th>
          <th>Логин</th>
          <th>Пароль</th>
          <th></th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>
            <Input placeholder="Метка" type="text"></Input>
          </td>
          <td>
            <Select>
              <SelectTrigger class="w-full">
                <SelectValue placeholder="Тип записи" />
              </SelectTrigger>
              <SelectContent>
                <SelectGroup>
                  <SelectItem value="local"> Локальная </SelectItem>
                  <SelectItem value="LDAP"> LDAP </SelectItem>
                </SelectGroup>
              </SelectContent>
            </Select>
          </td>
          <td>
            <Input placeholder="Логин" type="text" maxlength="100"></Input>
          </td>
          <td>
            <Input placeholder="Пароль" type="password" maxlength="100"></Input>
          </td>
          <td class="flex items-center h-9 justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 640 640"
              width="24"
              height="24"
            >
              <path
                d="M232.7 69.9L224 96L128 96C110.3 96 96 110.3 96 128C96 145.7 110.3 160 128 160L512 160C529.7 160 544 145.7 544 128C544 110.3 529.7 96 512 96L416 96L407.3 69.9C402.9 56.8 390.7 48 376.9 48L263.1 48C249.3 48 237.1 56.8 232.7 69.9zM512 208L128 208L149.1 531.1C150.7 556.4 171.7 576 197 576L443 576C468.3 576 489.3 556.4 490.9 531.1L512 208z"
              />
            </svg>
          </td>
        </tr>
        <tr>
          <td>
            <Input placeholder="Метка" type="text" maxlength="100"></Input>
          </td>
          <td>
            <Select>
              <SelectTrigger class="w-full">
                <SelectValue placeholder="Тип записи" />
              </SelectTrigger>
              <SelectContent>
                <SelectGroup>
                  <SelectItem value="local"> Локальная </SelectItem>
                  <SelectItem value="LDAP"> LDAP </SelectItem>
                </SelectGroup>
              </SelectContent>
            </Select>
          </td>
          <td>
            <Input placeholder="Логин" type="text" maxlength="100"></Input>
          </td>
          <td>
            <Input placeholder="Пароль" type="password" maxlength="100"></Input>
          </td>
          <td class="flex items-center h-9 justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 640 640"
              width="24"
              height="24"
            >
              <path
                d="M232.7 69.9L224 96L128 96C110.3 96 96 110.3 96 128C96 145.7 110.3 160 128 160L512 160C529.7 160 544 145.7 544 128C544 110.3 529.7 96 512 96L416 96L407.3 69.9C402.9 56.8 390.7 48 376.9 48L263.1 48C249.3 48 237.1 56.8 232.7 69.9zM512 208L128 208L149.1 531.1C150.7 556.4 171.7 576 197 576L443 576C468.3 576 489.3 556.4 490.9 531.1L512 208z"
              />
            </svg>
          </td>
        </tr>
        <tr>
          <td>
            <Input placeholder="Метка" type="text"></Input>
          </td>
          <td>
            <Select>
              <SelectTrigger class="w-full">
                <SelectValue placeholder="Тип записи" />
              </SelectTrigger>
              <SelectContent>
                <SelectGroup>
                  <SelectItem value="local"> Локальная </SelectItem>
                  <SelectItem value="LDAP"> LDAP </SelectItem>
                </SelectGroup>
              </SelectContent>
            </Select>
          </td>
          <td>
            <Input placeholder="Логин" type="text" maxlength="100"></Input>
          </td>
          <td>
            <Input placeholder="Пароль" type="password" maxlength="100"></Input>
          </td>
          <td class="flex items-center h-9 justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 640 640"
              width="24"
              height="24"
            >
              <path
                d="M232.7 69.9L224 96L128 96C110.3 96 96 110.3 96 128C96 145.7 110.3 160 128 160L512 160C529.7 160 544 145.7 544 128C544 110.3 529.7 96 512 96L416 96L407.3 69.9C402.9 56.8 390.7 48 376.9 48L263.1 48C249.3 48 237.1 56.8 232.7 69.9zM512 208L128 208L149.1 531.1C150.7 556.4 171.7 576 197 576L443 576C468.3 576 489.3 556.4 490.9 531.1L512 208z"
              />
            </svg>
          </td>
        </tr>
        <tr>
          <td>
            <Input placeholder="Метка" type="text"></Input>
          </td>
          <td>
            <Select>
              <SelectTrigger class="w-full">
                <SelectValue placeholder="Тип записи" />
              </SelectTrigger>
              <SelectContent>
                <SelectGroup>
                  <SelectItem value="local"> Локальная </SelectItem>
                  <SelectItem value="LDAP"> LDAP </SelectItem>
                </SelectGroup>
              </SelectContent>
            </Select>
          </td>
          <td>
            <Input placeholder="Логин" type="text" maxlength="100"></Input>
          </td>
          <td>
            <Input placeholder="Пароль" type="password" maxlength="100"></Input>
          </td>
          <td class="flex items-center h-9 justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 640 640"
              width="24"
              height="24"
            >
              <path
                d="M232.7 69.9L224 96L128 96C110.3 96 96 110.3 96 128C96 145.7 110.3 160 128 160L512 160C529.7 160 544 145.7 544 128C544 110.3 529.7 96 512 96L416 96L407.3 69.9C402.9 56.8 390.7 48 376.9 48L263.1 48C249.3 48 237.1 56.8 232.7 69.9zM512 208L128 208L149.1 531.1C150.7 556.4 171.7 576 197 576L443 576C468.3 576 489.3 556.4 490.9 531.1L512 208z"
              />
            </svg>
          </td>
        </tr>
        <tr>
          <td>
            <Input placeholder="Метка" type="text"></Input>
          </td>
          <td>
            <Select>
              <SelectTrigger class="w-full">
                <SelectValue placeholder="Тип записи" />
              </SelectTrigger>
              <SelectContent>
                <SelectGroup>
                  <SelectItem value="local"> Локальная </SelectItem>
                  <SelectItem value="LDAP"> LDAP </SelectItem>
                </SelectGroup>
              </SelectContent>
            </Select>
          </td>
          <td>
            <Input placeholder="Логин" type="text" maxlength="100"></Input>
          </td>
          <td>
            <Input placeholder="Пароль" type="password" maxlength="100"></Input>
          </td>
          <td class="flex items-center h-9 justify-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 640 640"
              width="24"
              height="24"
            >
              <path
                d="M232.7 69.9L224 96L128 96C110.3 96 96 110.3 96 128C96 145.7 110.3 160 128 160L512 160C529.7 160 544 145.7 544 128C544 110.3 529.7 96 512 96L416 96L407.3 69.9C402.9 56.8 390.7 48 376.9 48L263.1 48C249.3 48 237.1 56.8 232.7 69.9zM512 208L128 208L149.1 531.1C150.7 556.4 171.7 576 197 576L443 576C468.3 576 489.3 556.4 490.9 531.1L512 208z"
              />
            </svg>
          </td>
        </tr>
      </tbody>
    </table>
  </form>
</template>

<style scoped></style>
