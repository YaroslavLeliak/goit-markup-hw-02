# goit-markup-hw-02

/**
  |============================
  | Box of colors
  |============================
*/
:root {
  /*Fonts colors*/
  --button-color: #2196f3;
  --active-button-color: #188ce8;
  --team-content-color: #f5f4fa;
  --button-filters-color: #f5f4fa;
  /*Text colors*/
  --head-color: #212121;
  --content-color: #030202;
  --brand-color-left: #2196f3;
  --hover-color: #2196f3;
  --brand-color-right: #000000;
  --contacts-color: #757575;
  --text-head: #ffffff;
  --text-color: #757575;
  /*Background colors*/
  --main-background-color: #ffffff;
  --img--background-portfolio-color: #eeeeee;
  --bg-color: #2f303a;
}

/**
  |============================
  | General styles
  |============================
*/

body {
  font-family: "Roboto";
  font-size: 14px;
  color: var(--head-color);
  letter-spacing: 0.03em;
  background-color: var(--main-background-color);
}

/**
  |============================
  | Header styles
  |============================
*/

.brand {
  text-decoration: none;
  list-style: none;
  font-family: "Releway";
  font-weight: 700;
  font-size: 26px;
  line-height: 31px;
  letter-spacing: 0.03em;
  color: var(--brand-color-left);
}


.brand_right {
  color: var(--brand-color-right);
}

.brand_right_footer {
  color: var(--text-head);
}

.list-head {
  list-style: none;
  text-decoration: none;
  font-weight: 500;
  font-size: 14px;
  line-height: 16px;
  letter-spacing: 0.02em;
  color: var(--head-color);
}



.list-head .link-current {
  color: var(--hover-color);
}

.hover_color:hover,
.hover_color:focus {
  color: var(--hover-color);
}

.list-head-contacts {
  list-style: none;
  text-decoration: none;
  font-weight: 500;
  font-size: 14px;
  line-height: 16px;
  letter-spacing: 0.02em;
  color: var(--contacts-color);
}

/**
  |============================
  | Main styles
  |============================
*/

/*Effective decision*/

.eff_sol {
  background-color: var(--bg-color);
  text-align: center;
  width: 800px;
  height: 200px;
  left: 0px;
  top: 80px;
}

.eff_sol_h {
  color: var(--text-head);
  font-weight: 900;
  font-size: 44px;
  line-height: 60px;
  text-align: center;
  letter-spacing: 0.06em;
  text-transform: uppercase;
}

.button-color {
  color: var(--main-background-color);
  background-color: var(--button-color);
  cursor: pointer;
  text-align: center;
}

.button-color:hover,
.button-color:focus {
  color: var(--main-background-color);
  background-color: var(--active-button-color);
}

/*Strengths*/

.visually-hidden {
  position: absolute;
  white-space: nowrap;
  width: 1px;
  height: 1px;
  overflow: hidden;
  border: 0;
  padding: 0;
  clip: rect(0 0 0 0);
  clip-path: inset(50%);
  margin: -1px;
}

.str_titel {
  font-weight: 700;
  font-size: 14px;
  line-height: 16px;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  color: var(--head-color);
}

.str_txt {
  font-weight: 400;
  font-size: 14px;
  line-height: 24px;
  letter-spacing: 0.03em;
  color: var(--text-color);
}

/*Foto*/

.foto_titel {
  font-weight: 700;
  font-size: 36px;
  line-height: 42px;
  text-align: center;
  letter-spacing: 0.03em;
  color: var(--head-color);
}

/*Team members*/

.list{
  text-decoration: none;
  list-style: none;
}

.team_bck {
  background-color: var(--team-content-color);
}

.team_title {
  font-weight: 700;
  font-size: 36px;
  line-height: 42px;
  text-align: center;
  letter-spacing: 0.03em;
  color: var(--head-color);
}

.team-name {
  font-weight: 500;
  font-size: 16px;
  line-height: 19px;
  text-align: center;
  letter-spacing: 0.03em;
  color: var(--head-color);
}

.team-txt {
  font-weight: 400;
  font-size: 16px;
  line-height: 19px;
  text-align: center;
  letter-spacing: 0.03em;
  color: var(--text-color);
}

/**
  |============================
  | Footer Style
  |============================
*/
.footer {
  background-color: var(--bg-color);
  text-decoration: none;
  list-style: none;
  font-weight: 500;
  line-height: 1.14;
  letter-spacing: 0.02em;
}

.adress {text-decoration: none;
  list-style: none;}

.list_footer_map {
  text-decoration: none;
  list-style: none;
  font-weight: 400;
  font-size: 14px;
  line-height: 24px;
  letter-spacing: 0.03em;
  color: var(--text-head);
}


.list_footer {
  text-decoration: none;
  list-style: none;
  font-weight: 400;
  font-size: 14px;
  line-height: 24px;
  letter-spacing: 0.03em;
  color: rgba(255, 255, 255, 0.6);
}

/**
  |============================
  | Portfolio
  |============================
*/

.button-portfolio-color:hover,
.button-portfolio-color:focus {
  color: var(--text-head);
  background-color: var(--button-color);
  font-weight: 500;
  font-size: 16px;
  line-height: 26px;
  text-align: center;
  letter-spacing: 0.03em;
}

.button-portfolio-color {
  color: var(--head-color);
  background-color: var(--button-filters-color);
  cursor: pointer;
}

.port_list{
  text-decoration: none;
  list-style: none;
}

.port_titel {
  font-weight: 700;
  font-size: 18px;
  line-height: 15px;
  letter-spacing: 0.06em;
  color: var(--head-color);
}

.port_txt {
  font-weight: 400;
  font-size: 16px;
  line-height: 30px;
  letter-spacing: 0.03em;
  color: var(--text-color);
}


a{text-decoration: none;
  list-style: none;
  color: var(--head-color);
}