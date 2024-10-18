<template>
    <div id="burguer-table">
        <div>
            <div id="burguer-table-heading">
                <div class="order-id">#:</div>
                <div>Cliente:</div>
                <div>Pao:</div>
                <div>Carne:</div>
                <div>Opcionais</div>
                <div>Ações:</div>
            </div>
        </div>
        <div id="burguer-table-rows">
            <div class="burguer-table-row">
                <div class="order-number">1</div>
                <div>João</div>
                <div>Pão de trigo</div>
                <div>Maminha</div>
                <div>
                    <ul>
                        <li>Salame</li>
                        <li>Tomate</li>
                    </ul>
                </div>
                <div>
                    <select name="status" class="status">
                        <option value="">Selecione o status do hamburguer</option>
                    </select>
                    <button class="delete-btn">Cancelar</button>
                </div>
            </div>
        </div>
    </div>

</template>

<script>
export default {

}
</script>

<style scoped>
    #burguer-table {
        max-width: 1200px;
        margin: 0 auto;
    }

    #burguer-table-heading,
    #burguer-table-rows,
    .burguer-table-tow {
        display: flex;
        flex-wrap: wrap;
    }

    #burguer-table-heading {
        font-weight: bold;
        padding: 12px;
        border-bottom: 3px solid #333; 
    }
</style>