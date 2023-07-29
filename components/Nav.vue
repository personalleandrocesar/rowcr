<template>
    <div class='nav
    '>
        <div>
            <div>
                <a @click="$router.go(-1)"><i class="fas main-l fa-arrow-left"></i></a>
            </div>
        </div>
    </div>

</template>
<style scoped>
.nav
{
  height: 35px;
  position: sticky;
  top: -1px;
  background-color: var(--color-background);    
  border-radius: 0% 0% 10% 10%;
  z-index: 10;
}

.nav
 div{
  display: flex;
  justify-content: space-between;
  flex-direction: row;
}

.nav
 a{
  cursor: pointer;
  text-decoration: none;
  margin: 0 14px 0 6px;
  font-size: 1.2em;
}

.nav a:hover {
  background-color: transparent;
  color: #00bd7e;
}
.nav
 i {
  color: #aaa;
  margin-top: 8px;
  display: flex;
  justify-content: flex-end;
}

.nav
 i:hover {
  color: #00bd7e;
  margin-top: 8px;
  display: flex;
  justify-content: flex-end;
}
</style>
