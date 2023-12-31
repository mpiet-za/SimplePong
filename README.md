
<a name="start"></a>

<!-- HEADER -->

<br />
<div align="center">
  <a href="https://github.com/mpiet-za/TileTower">
    <img src="https://avatars.githubusercontent.com/u/63480247?v=4" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">SimplePong (Java)</h3>

  <p align="center">
    Java implementation of the pong game.
  </p>
</div>

<!-- INFORMATION -->

## About

A simple implementation of the popular *pong* game in Java.

![GitHub Issues](https://img.shields.io/github/issues/mpiet-za/SimplePong?style=flat-square&label=Issues&labelColor=%23161b22&color=%234169E1)
![GitHub Stars](https://img.shields.io/github/stars/mpiet-za/SimplePong?style=flat-square&label=Stars&labelColor=%23161b22&color=%234169E1)


**Compete in a head-on competition against yourself or your friends in this two-dimensional, local multiplayer implementation of paddle pong! Who will be the last one standing?**

As a relatively novice Java programmer in his first year studying Computer & Information Sciences at University, this project stands out as a significant milestone, straying from the prescribed syllabus into the vast world of continuous self-studies. I wanted a break from the usual development of mundane desktop apllications, and decided to learn how to create dynamic and lightweight graphical minigames.

The graphical user interface (GUI) is hosted within a JFrame and JPanel from the native Swing libraries, with the game elements being drawn onto the JPanel using Graphics(2D) methods. The game elements are updated by event listeners that are bound to keyboard inputs – see table below for controls. Collisions are detected by using crude co-ordinate based colliders, and similarly, the movement also inherets this co-ordinate based system.

| SIDE | UP     | DOWN   |
| :--: | :----: | :----: |
| `L`  | `VK_Q` | `VK_W` |
| `R`  | `VK_O` | `VK_P` |

| TO RESTART |
| :--------: |
| VK_ENTER   |

<p align="right">(<a href="#start">Top</a>)</p>

<!-- LICENSE -->

## License

Ditributed under the **GPLv3 License**, see documentation for more information.

<p align="right">(<a href="#start">Top</a>)</p>