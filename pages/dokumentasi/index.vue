    <template>
        <div class="container">
            <div class="content">
                <div class="grid-item"> 
                    <div>
                    <img src="/assets/img/Mabit_Irma.jpg" alt="Mabit IRMA">
                    <h3>Mabit Irma</h3>
                </div>
                <div>
                    <img src="/assets/img/Pkrm_Irma.jpg" alt="Pkrm rma">
                    <h3>Pkrm Irma</h3>
                </div>
                <div>
                    <img src="/assets/img/Isra_Miraj.jpg" alt="Isra Mi'raj">
                    <h3>Isra Mi'raj</h3>
                </div>
                <div>
                    <img src="/assets/img/Kajian_Rutin.jpg" alt="Kajian Rutin">
                    <h3>Kajian Rutin Hari Selasa</h3>
                </div>
                <div>
                    <img src="/assets/img/Pergantian_Irma.jpg" alt="Pergantian Irma">
                    <h3>Pergantian Kepengurusan</h3>
                </div>
            </div>
        </div>
    </div>
            
    </template>
    
    <style scoped>
            body {
                font-family: Arial, sans-serif;
                background-color: #f5f5f5;
                margin: 0;
                padding: 0;
            }
            .container {
                max-width: 1000px;
                margin: 20px auto;
                background-color: white;
                padding: 20px;
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            }
            .header {
                text-align: center;
                background-color: #007b43;
                color: white;
                padding: 20px 0;
            }
            .header img {
                width: 80px;
                vertical-align: middle;
                
            }
            .header h1 {
                display: inline-block;
                margin-left: 20px;
            }
            .content {
                display: grid;
                grid-template-columns: 1fr 1fr;
                gap: 20px;
                margin-top: 20px;
            }
            .content img {
                width: 100%;
                height: auto;
                border-radius: 50px;
            }
            .content h3 {
                text-align: center;
                margin-top: 20px;
            }
            
        </style>