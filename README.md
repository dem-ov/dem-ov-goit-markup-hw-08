.footer-menu {
  padding-top: 60px;
  padding-bottom: 60px;
  background-color: var(--best-color6);
  margin: 0 auto;
}

.footer-adr {
  @media screen and (min-width: 768px) {
    justify-content: space-around;
    align-items: baseline;
    display: flex;
    flex-wrap: wrap;
  }

  @media screen and (min-width: 1200px) {
    display: flex;
  }
}

.contact-list {
  list-style-type: none;
  font-style: normal;
  display: block;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  margin-top: 20px;
  gap: 8px;

  &__adr {
    text-decoration: none;
    font-family: "Roboto", sans-serif;
    font-size: 14px;
    font-weight: 400;
    line-height: 1.71;
    letter-spacing: 0.03em;
    text-align: left;
    color: var(--best-color8);
  }

  &__mail {
    text-decoration: none;
    height: 21px;
    width: 231px;
    left: 215px;
    top: 2235px;
    border-radius: nullpx;
    color: var(--best-color9);
    font-family: "Roboto", sans-serif;
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.03em;
  }

  &__tel {
    text-decoration: none;
    height: 21px;
    width: 231px;
    left: 215px;
    top: 2235px;
    border-radius: nullpx;
    color: var(--best-color9);
    font-family: "Roboto", sans-serif;
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.03em;
  }
  @media screen and (min-width: 1200px) {
    justify-content: space-around;
    align-items: baseline;
    display: flex;
  }
}

.conect-all {
  margin-top: 60px;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  // margin-right: 93px;
  color: white;
  text-transform: uppercase;
  font-family: Roboto;
  font-size: 14px;
  font-weight: 700;
  line-height: 16px;
  letter-spacing: 0.03em;
  text-align: left;

  @media screen and (min-width: 768px) {
    margin-top: 0px;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    // margin-right: 93px;
    color: white;
    text-transform: uppercase;
    font-family: Roboto;
    font-size: 14px;
    font-weight: 700;
    line-height: 16px;
    letter-spacing: 0.03em;
    text-align: left;
  }

  @media screen and (min-width: 1200px) {
    margin-right: 93px;
    color: white;
    text-transform: uppercase;
    font-family: Roboto;
    font-size: 14px;
    font-weight: 700;
    line-height: 16px;
    letter-spacing: 0.03em;
    text-align: left;
  }
}

.connect-list {
  list-style: none;
  display: flex;
  margin-top: 20px;
  gap: 10px;
}

.adr-items {
  @media screen and (min-width: 768px) {
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    margin-bottom: 60px;
  }
  @media screen and (min-width: 1200px) {
    align-items: flex-start;
    margin-right: 0px;
    margin-bottom: 0px;
  }
}

.mailing-list {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 700;
  font-size: 14px;
  line-height: 16px;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  color: #ffffff;
  display: flex;
  flex-direction: column;
  align-items: center;

  @media screen and (min-width: 768px) {
    align-items: center;
    flex-direction: column;
  }

  @media screen and (min-width: 1200px) {
    display: flex;
    gap: 20px;
    margin-top: 20px;
  }

  &__email {
    margin-top: 20px;
    display: flex;

    flex-direction: column;
    gap: 20px;

    @media screen and (min-width: 768px) {
      align-items: center;
      align-content: normal
    }
  }
}

.connect-list__link {
  fill: white;
  border-radius: 50%;
  background-color: #ffffff1a;
  padding: 12;
  display: flex;
  padding: 12px;
  margin: 0px;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);

  &:hover {
    background-color: #2196f3;
  }

  &:focus {
    background-color: #2196f3;
  }
}

.contacts :not(:last-child) {
  margin-bottom: 9px;
}
.form-batton {
  width: 200px;
  height: 50px;
  left: 1213px;
  top: 2794px;
  background: #2196f3;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
  border-radius: 4px;
  font-family: "Roboto";
  font-style: normal;
  font-weight: 700;
  font-size: 16px;
  line-height: 30px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  letter-spacing: 0.06em;
  color: #ffffff;
  fill: var(--best-color2);
  gap: 10px;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
  cursor: pointer;
  border: none;

  &:focus {
    border-radius: 4px;
    background-color: #188ce8;
  }

  &:hover {
    background-color: #188ce8;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
  }

  &:active {
    background-color: #188ce8;
  }
}
.input {
  box-sizing: border-box;
  justify-items: center;
  align-items: center;
  width: 358px;
  height: 50px;
  left: 815px;
  top: 2784px;
  background-color: #2f303a;
  border: 1px solid rgba(255, 255, 255, 0.3);
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.15));
  border-radius: 4px;
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  padding: 0 16px;
  cursor: pointer;

  &:focus {
    border: var(--best-color1) 1px solid;
    transition: border-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
  }

  &:hover {
    border: var(--best-color1) 1px solid;
    transition: border-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
  }
}
