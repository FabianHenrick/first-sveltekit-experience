<div class="flex flex-col  gap-10 justify-center items-center text-center">
    <h1 class="text-3xl font-bold underline justify-center ">
        Desafio Lesser
    </h1>



    <div class="card w-96 bg-neutral text-neutral-content  ">
        <div class="card-body items-center text-center">
          <h2 class="card-title">Tempo Restante</h2>
          <div class="flex">
          <p>0</p>
          <p>0</p>
          <p>:</p>
          <p>1</p>
          <p>5</p></div>
          
            <button class="btn btn-primary">Enviar</button>
          </div>
      </div>

    <div class="card w-112 bg-neutral text-neutral-content ">
        <div class="card-body items-center text-center">
            <form method="POST" class="flex flex-col gap-2 ">
                
                <label >Nome: <input name="Name" type="Name" required> </label>
                <label for="phone"> Telefone:  <input type="tel" id="phone" name="phone" required /></label>
            
                <label for="email">Email:<input type="email" id="email" pattern=".+@example\.com" size="40" required /></label>

                <!-- Open the modal using ID.showModal() method -->
                <button class="btn" onclick="my_modal_1.showModal()">Enviar</button>
                <dialog id="my_modal_1" class="modal">
                <div class="modal-box">
                    
                      <form method="dialog f" class="flex space-x-80">
                        <!-- if there is a button in form, it will close the modal -->
                        <h3 class="font-bold text-lg ">Resultado</h3>
                         <button class="btn">X</button>
                    </form> 
                    <h3 class="font-bold text-lg text-emerald-500">Você Concluíu o Desafio</h3>
                    <h3 class="font-bold text-lg text-red-500">Você Falhou no Desafio</h3>
                    <div class="modal-action">
                    
                    </div>
                </div>
                </dialog>
            </form>
        </div>
    </div>
</div>    





