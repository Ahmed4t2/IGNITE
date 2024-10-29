# IGNITE
Marketing
// App.js
import React from 'react';
import { View, Text, Button, StyleSheet } from 'react-native';

export default function App() {
  return (
    <View style={styles.container}>
      <Text style={styles.title}>أهلاً بك في Ignite</Text>
      <Button title="تحرير فيديو" onPress={() => {}} />
      <Button title="تحليل الأداء" onPress={() => {}} />
      <Button title="نشر تلقائي" onPress={() => {}} />
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#fff',
    alignItems: 'center',
    justifyContent: 'center',
  },
  title: {
    fontSize: 24,
    fontWeight: 'bold',
    marginBottom: 20,
  },
});
