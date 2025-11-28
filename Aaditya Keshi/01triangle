from OpenGL.GL import *
from OpenGL.GLUT import *
from OpenGL.GLU import *

def draw():
    glClear(GL_COLOR_BUFFER_BIT)
    glBegin(GL_TRIANGLES)
    glColor3f(1, 0, 0)          # Red color
    glVertex2f(-0.5, -0.5)      # First vertex
    glColor3f(0, 1, 0)          # Green color
    glVertex2f(0.5, -0.5)       # Second vertex
    glColor3f(0, 0, 1)          # Blue color
    glVertex2f(0.0, 0.5)        # Third vertex
    glEnd()
    glFlush()

glutInit()
glutCreateWindow(b"Triangle using PyOpenGL")
glutDisplayFunc(draw)
glutMainLoop()
