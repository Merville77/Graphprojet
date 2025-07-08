import networkx as nx
import matplotlib.pyplot as plt
import numpy as np


def choisir_couleur_type(type_noeud):
    """Retourne une couleur et une forme basées sur le type de nœud"""
    couleurs_types = {
        'hopital': {'color': '#4A90E2', 'shape': 'o'},
        'pharmacie': {'color': '#7ED321', 'shape': 's'},
        'docteur': {'color': '#F5A623', 'shape': '^'},
        'infirmiere': {'color': '#9013FE', 'shape': 'D'},
        'patient': {'color': '#D0021B', 'shape': 'v'},
        'ambulance': {'color': '#FF6B35', 'shape': 'p'},
        'pays': {'color': '#4A4A4A', 'shape': 'h'},
        'ville': {'color': '#8B572A', 'shape': 'H'},
        'quartier': {'color': '#417505', 'shape': '8'},
        'continent': {'color': '#2E3440', 'shape': '*'},
        'default': {'color': '#666666', 'shape': 'o'}
    }

    return couleurs_types.get(type_noeud.lower(), couleurs_types['default'])


def saisir_noeuds():
    """Permet à l'utilisateur de saisir les nœuds"""
    print("=== SAISIE DES NŒUDS ===")

    while True:
'pays': {'color': '#4A4A4A', 'shape': 'h'},
        'ville': {'color': '#8B572A', 'shape': 'H'},
        'quartier': {'color': '#417505', 'shape': '8'},
        'continent': {'color': '#2E3440', 'shape': '*'},
        'default': {'color': '#666666', 'shape': 'o'}
    }

    return couleurs_types.get(type_noeud.lower(), couleurs_types['default'])


def saisir_noeuds():
    """Permet à l'utilisateur de saisir les nœuds"""
    print("=== SAISIE DES NŒUDS ===")

    while True:


    
