# 2D Character Controller user guide

## CharacterController2D

This script can be applied to a `GameObject` to give it basic movement and jumping capabilities in 2D. It should have a `Rigidbody2D` attached in order to function correctly. Note that this script does not handle input or determine the movement speed by itself.

## MovePlayer

This script works in conjunction with `CharacterController2D` to allow the player to controller the `GameObject`'s movement. To use, apply this script to a `GameObject` containing the `CharacterController2D` script, then attach `CharacterController2D` to the `Controller` slot in the MovePlayer script.
