# Contrato Inteligente de Venta de Tokens

## Descripción del Proyecto

Este proyecto es un contrato inteligente para una venta de tokens, implementado en Solidity. Utiliza la biblioteca OpenZeppelin para un desarrollo de contratos seguro y robusto. El contrato permite a los usuarios comprar tokens enviando Ether, con la capacidad de congelar el contrato y establecer precios de tokens.

## Estructura del Proyecto

- **Contratos**: El contrato principal es `PrivateSale.sol`, que maneja la lógica de la venta de tokens.
- **Contratos de OpenZeppelin**:
  - **Acceso**: Gestiona mecanismos de propiedad y control de acceso.
  - **Seguridad**: Proporciona utilidades de seguridad como guardias de reentrada.
  - **Token**: Implementa estándares e interfaces de tokens ERC20.
  - **Utilidades**: Ofrece funciones de utilidad para direcciones y otras operaciones comunes.

## Tecnología

- **Solidity**: El contrato inteligente está escrito en Solidity, un lenguaje diseñado específicamente para desarrollar contratos inteligentes en la blockchain de Ethereum.
- **OpenZeppelin**: Una biblioteca para el desarrollo seguro de contratos inteligentes, que proporciona implementaciones probadas de estándares ERC y otras utilidades.

## Alcance

El alcance de este proyecto incluye:

- Implementar un contrato de venta de tokens que permita a los usuarios comprar tokens con Ether.
- Proporcionar mecanismos para congelar el contrato y ajustar los precios de los tokens.
- Asegurar la seguridad contra ataques de reentrada y otras vulnerabilidades comunes.

## Cómo Usar

1. **Despliegue**: Despliegue el contrato `TokenSale` en una red de Ethereum.
2. **Configuración**: Establezca la dirección del token, la dirección de retención y el precio inicial.
3. **Compra de Tokens**: Los usuarios pueden llamar a la función `buy` para comprar tokens enviando Ether.
4. **Funciones de Administración**: El propietario del contrato puede congelar/descongelar el contrato y establecer precios de tokens.
