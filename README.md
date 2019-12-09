# Ang7toggleDiv

<div class="row">
    <div class="col text-center crypto">
      <span><button class="crypto-btn" id="cryptoBtn" [ngClass]="{'active-btn' : selectedState == 'crypto'}"
          (click)="changeState();getDashboardBalanceData();">{{'DASHBOARD.cryptoCurrency.toggle' | translate}}</button></span>
      <span><button class="pesos-btn" id="pesosBtn" [ngClass]="{'active-btn' : selectedState == 'pesos'}"
          (click)="selectedState='pesos';getDashboardBalanceData();">{{'DASHBOARD.pesos.toggle' | translate}}</button></span>
    </div>
  </div>
